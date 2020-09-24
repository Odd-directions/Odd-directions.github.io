---
title: Stories
nav: Stories
layout: default
meta: Storied by Odd Directions.
changefreq: monthly
---

This is a feed of the stories that Tobias has written:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
