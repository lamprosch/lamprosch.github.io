---

layout: default
title: Blog
permalink: /blog/
---

## Blog

Here I share workflow notes, production breakdowns, and reflections on sound.

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date"> — {{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
