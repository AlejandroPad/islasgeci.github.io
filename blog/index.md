---
layout: page
title: Blog
tagline: Ciencia de Datos • GECI
---

<ul>
  {% for post in site.posts %}
    <li>
      <b><a href="{{ post.url }}">{{ post.title }}</a></b>
      <i>{{ post.date | date_to_string }} - {{ post.name }} -  {{ page.name }} </i>
    </li>
  {% endfor %}
</ul>
