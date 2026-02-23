---
layout: custom
title: Poems
permalink: /categories/poems/
---

# Poems

Here are all my Poem entries:

<ul>
  {% for post in site.categories['poems'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%B %d, %Y" }}</em>
    </li>
  {% endfor %}
</ul>