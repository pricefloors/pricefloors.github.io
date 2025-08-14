---
layout: default
title: Welcome to My Blog
---

![A photo of me](assets/me.png)

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
