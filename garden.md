---
layout: page
title: Garden
permalink: /garden/
---

This is the gateway to my garden and notes collection.

<ul>
  {% for item in site.garden %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>
