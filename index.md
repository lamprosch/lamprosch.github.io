---

layout: default

title: Home

---



\# Welcome



\## Portfolio

<ul>

{% for item in site.portfolio %}

&nbsp; <li>

&nbsp;   <a href="{{ item.url | relative\_url }}">{{ item.title }}</a>

&nbsp;   — <small>{{ item.excerpt }}</small>

&nbsp; </li>

{% endfor %}

</ul>



\## Technical

<ul>

{% for item in site.technical %}

&nbsp; <li>

&nbsp;   <a href="{{ item.url | relative\_url }}">{{ item.title }}</a>

&nbsp;   — <small>{{ item.excerpt }}</small>

&nbsp; </li>

{% endfor %}

</ul>



\## Latest posts

<ul>

{% for post in site.posts limit:5 %}

&nbsp; <li><a href="{{ post.url | relative\_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>

{% endfor %}

</ul>

