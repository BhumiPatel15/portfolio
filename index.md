---
# 👇 This "front matter" tells Jekyll how to treat the page.
# "layout: default" means use the theme's default template.
# "title" sets the browser tab title and is used in some themes.
layout: default
title: Home
---

<!-- HERO -->
<section class="hero">
  <div class="container">
    <h1 class="name">Bhumi Patel</h1>
    <p class="subtitle">Cybersecurity Graduate Student · Cloud Security Enthusiast</p>
    <div class="cta">
      <a class="btn" href="{{ '/projects/' | relative_url }}">View Projects</a>
      <a class="btn" href="{{ '/contact/' | relative_url }}">Contact Me</a>
      <a class="btn" href="{{ '/about/' | relative_url }}">About Me</a>
    </div>
  </div>
</section>

<!-- QUICK LINKS SECTION -->
<section class="section">
  <h2>Explore</h2>
  <ul class="quicklinks">
    <li><a href="{{ '/about/' | relative_url }}">About Me</a></li>
    <li><a href="{{ '/work/' | relative_url }}">Work Experience</a></li>
    <li><a href="{{ '/education/' | relative_url }}">Education</a></li>
    <li><a href="{{ '/projects/' | relative_url }}">Projects</a></li>
    <li><a href="{{ '/organizations/' | relative_url }}">Organizations</a></li>
    <li><a href="{{ '/volunteer/' | relative_url }}">Volunteer & Conferences</a></li>
    <li><a href="{{ '/contact/' | relative_url }}">Contact</a></li>
  </ul>
</section>

