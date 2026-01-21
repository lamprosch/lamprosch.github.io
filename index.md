---
layout: default
title: Home
---

# Lampros Ch

<div class="home-hero">
  <h1>Lampros Chantzis</h1>
  <p>Audio engineer, researcher, and educator based in Barcelona.  
  I create immersive sound experiences and help students grow through clear, practical music lessons.</p>
</div>


## Featured

<div class="featured-section">
  <ul class="featured-list">
    <li><strong>Portfolio:</strong> <a href="{{ site.portfolio | first | relative_url }}">{{ site.portfolio | first.title }}</a></li>
    <li><strong>Technical:</strong> <a href="{{ site.technical | first | relative_url }}">{{ site.technical | first.title }}</a></li>
    <li><strong>Lessons:</strong> <a href="/lessons/">Guitar & Music Theory Lessons</a></li>
  </ul>
</div>


### Portfolio
{% assign featured_portfolio = site.portfolio | first %}
- [{{ featured_portfolio.title }}]({{ featured_portfolio.url | relative_url }})

### Technical
{% assign featured_technical = site.technical | first %}
- [{{ featured_technical.title }}]({{ featured_technical.url | relative_url }})

### Lessons
- [Guitar & Music Theory Lessons](/lessons/)

## Explore
<div class="section-grid">
  <a class="section-card" href="/portfolio/">Portfolio</a>
  <a class="section-card" href="/technical/">Technical</a>
  <a class="section-card" href="/lessons/">Lessons</a>
  <a class="section-card" href="/blog/">Blog</a>
</div>