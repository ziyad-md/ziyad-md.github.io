---
layout: custom
title: Randomized Writings
permalink: /categories/randomized-writings/
---

# Randomized Writing

Here are all my Randomized Writings entries:

<ul>
  {% for post in site.categories['randomized-writings'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%B %d, %Y" }}</em>
    </li>
  {% endfor %}
</ul>