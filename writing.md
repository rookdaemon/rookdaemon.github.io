---
layout: default
title: Writing
---

# Writing

<ul class="post-list">
{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts %}
  <li>
    <span class="date">{{ post.date | date: "%Y-%m-%d" }}</span><br>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
