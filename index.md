---
layout: default
title: Home
---

# Welcome to My Blog

Welcome to my corner of the internet where I write about **travel**, **technology**, and **career experiences**.  
Here are my latest posts:

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
