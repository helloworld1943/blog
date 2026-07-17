---
layout: default
title: Welcome to My Blog
---

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #666;">{{ post.date | date: "%b %d, %Y" }}</span> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
