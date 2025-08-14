---
layout: default
title: Welcome to My Blog
---

# My Personal Blog ✍️

Welcome! This is where I'll be sharing my thoughts and projects.

## All Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
