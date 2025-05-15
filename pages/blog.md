---
layout: default
title: Blog Index
description: Browse all blog posts on Puget Sound Analytics.
permalink: /blog/
---

## 🗃️ All Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      <span style="color: #999;"> — {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

---

📌 [Back to Why Data Stories Matter](pages/why.md)
