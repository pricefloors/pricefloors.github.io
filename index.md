---
layout: default
title: Welcome to My Blog
---

<img src="assets/me.png" width="150" alt="A photo of me smiling">

Welcome! My name is Name, and this is where I'll be sharing my thoughts and projects.

---

## All Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - *{{ post.read_time }}*
    </li>
  {% endfor %}
</ul>
