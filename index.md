---
layout: default
title: Welcome to My Blog
---

<table style="border: none; background: none;">
  <tr style="border: none; background: none;">
    <td style="border: none; padding-right: 20px; vertical-align: top;">
      <img src="assets/me.heic" width="150" alt="A photo of me smiling">
    </td>
    <td style="border: none; vertical-align: top;">
      <p>Welcome! My name is [Your Name], and this is where I'll be sharing my thoughts and projects.</p>
    </td>
  </tr>
</table>

---

## All Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - *{{ post.read_time }}*
    </li>
  {% endfor %}
</ul>
