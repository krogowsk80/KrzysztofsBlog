---
layout: single
title: ""
permalink: /case-studies/
author_profile: true
classes: wide
---

<div class="insights-header">
  <span class="insights-subtitle">In Practice</span>
  <h2 class="insights-title">Success Stories</h2>
</div>

<div class="insights-grid">
{% for post in site.categories['Case Studies'] %}
  <div class="insight-card">
    <div class="insight-image-container">
      {% if post.header.teaser %}
        <img src="{{ post.header.teaser | relative_url }}" alt="{{ post.title }}" class="insight-image" />
      {% else %}
        <span class="material-symbols-outlined" style="color: rgba(0, 229, 255, 0.4); font-size: 24px;">dataset</span>
      {% endif %}
    </div>
    <div class="insight-content">
      <span class="insight-tag">{{ post.tags[0] | default: post.categories[0] | default: "Case Study" }}</span>
      <h3 class="insight-card-title"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <span class="insight-date">{{ post.date | date: "%b %d, %Y" }}</span>
    </div>
  </div>
{% endfor %}
</div>