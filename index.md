---
layout: default
title: Welcome to My Blog
---

<img src="assets/profile.jpg" width="150" alt="A photo of me smiling">

# My Personal Blog ✍️

Welcome! My name is [Your Name], and this is where I'll be sharing my thoughts and projects.

---

## All Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
