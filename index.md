---
layout: default
title: Home
---

# Latest Posts

## 🧠 Tech
<ul class="post-list">
  {% assign tech_posts = site.tech_posts | sort: 'date' | reverse %}
  {% for post in tech_posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

## 🌍 Travel
<ul class="post-list">
  {% assign travel_posts = site.travel_posts | sort: 'date' | reverse %}
  {% for post in travel_posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

## 🧠 Philosophy
<ul class="post-list">
  {% assign posts = site.posts | sort: 'date' | reverse %}
  {% for post in posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>