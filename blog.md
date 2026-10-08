---
layout: page
title: Blog
published: false
---

Occasional notes on research, building tools, and the PhD life. No schedule, no newsletter — just things I wish someone had told me.

<ul class="blog-index">
{% for post in site.posts %}
  <li>
    <span class="post-date">{{ post.date | date: "%B %-d, %Y" }}</span> —
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
