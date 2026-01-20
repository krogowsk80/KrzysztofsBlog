---
layout: single
title: "Case Studies"
permalink: /case-studies/
author_profile: true
classes: wide
---

<style>
  .archive__item {
    transition: all 0.3s ease-in-out;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 10px;
    background: #fff;
  }
  .archive__item:hover {
    transform: translateY(-5px) scale(1.02);
    box-shadow: 0 10px 20px rgba(0,0,0,0.15);
  }
</style>

{% for post in site.categories['Case Studies'] %}
  {% include archive-single.html %}
{% endfor %}