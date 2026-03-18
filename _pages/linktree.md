---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Dive Craft - Links</title>
    <!-- Placeholder for Google Analytics tracking code -->
    <!-- 
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXXX-X"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());
      gtag('config', 'UA-XXXXXXXXX-X');
    </script>
    -->
    <style>
        :root {
            --primary-color: #1a1a1a; /* Professional dark charcoal */
            --secondary-color: #2c3e50; /* Deep blue-grey */
            --accent-color: #3498db; /* Professional blue */
            --bg-color: #f4f7f6; /* Soft light grey/white background */
            --text-color: #333;
            --button-bg: #ffffff;
            --button-text: #1a1a1a;
            --button-border: #e0e0e0;
            --button-hover-bg: #f0f0f0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 40px 20px;
            box-sizing: border-box;
        }

        .container {
            width: 100%;
            max-width: 600px;
            text-align: center;
        }

        .profile-container {
            margin-bottom: 24px;
        }

        .profile-image {
            width: 96px;
            height: 96px;
            border-radius: 50%;
            background-color: #ccc; /* Placeholder color */
            margin: 0 auto 16px;
            display: block;
            border: 3px solid #fff;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            object-fit: cover;
        }

        .brand-logo {
            width: 120px;
            height: auto;
            margin-bottom: 12px;
            opacity: 0.9;
            display: block;
            margin: 0 auto 12px;
        }

        h1 {
            font-size: 1.25rem;
            font-weight: 700;
            margin: 0 0 8px;
            color: var(--primary-color);
        }

        .description {
            font-size: 0.95rem;
            color: #666;
            margin-bottom: 32px;
            line-height: 1.5;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 16px;
            width: 100%;
        }

        .link-button {
            display: block;
            background-color: var(--button-bg);
            color: var(--button-text);
            text-decoration: none;
            padding: 16px;
            border-radius: 8px;
            font-weight: 600;
            font-size: 1rem;
            transition: all 0.2s ease;
            border: 1px solid var(--button-border);
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .link-button:hover {
            background-color: var(--button-hover-bg);
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            border-color: var(--accent-color);
        }

        .footer {
            margin-top: auto;
            padding-top: 40px;
            font-size: 0.85rem;
            color: #999;
        }

        /* Mobile specific adjustments */
        @media (max-width: 480px) {
            body {
                padding: 30px 15px;
            }
            .link-button {
                padding: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-container">
            <!-- Circular placeholder for a profile image -->
            <div class="profile-image" style="background-image: url('/assets/images/bio-photo.jpg'); background-size: cover; background-position: center;">
                <!-- If image is missing, it shows the background color -->
            </div>
            
            <!-- Branding logo placeholder -->
            <!-- <img src="/assets/images/site-logo.png" alt="Data Dive Craft Logo" class="brand-logo"> -->
            
            <h1>Data Dive Craft</h1>
            <p class="description">Strategic data architecture, high-performance engineering and production-grade design with Augentic AI</p>
        </div>

        <div class="links-container">
            <a href="http://datadivecraft.com/insights/" class="link-button" target="_blank">Insights</a>
            <a href="http://datadivecraft.com/case-studies/" class="link-button" target="_blank">Case Studies</a>
            <a href="http://datadivecraft.com/contact/" class="link-button" target="_blank">Contact Me</a>
        </div>

        <footer class="footer">
            &copy; 2026 Data Dive Craft. All rights reserved.
        </footer>
    </div>
</body>
</html>
