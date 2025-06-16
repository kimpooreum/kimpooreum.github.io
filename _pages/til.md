---
layout: default
title: TIL
permalink: /til/
---

# 📝 Today I Learned (TIL)

<ul>
  {% for post in site.categories.TIL %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

