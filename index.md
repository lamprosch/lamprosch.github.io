---
layout: default
title: Home
---

# Lampros Ch

Audio engineer, researcher, and educator based in Barcelona.  
I create immersive sound experiences and help students grow through clear, practical music lessons.

## Featured

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