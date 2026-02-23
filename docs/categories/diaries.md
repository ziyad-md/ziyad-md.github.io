---
layout: custom
title: Diaries
permalink: /categories/diaries/
---

# My Diaries

Here are all my diary entries:

<ul>
  {% for post in site.categories['diaries'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%B %d, %Y" }}</em>
    </li>
  {% endfor %}
</ul>