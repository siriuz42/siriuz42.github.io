---
layout: default
title: Blog
---

Blog
===========

<ul>
  {% for post in site.posts %}
    <li>
      [{{post.date | date: "%x" }}] <a href="{{ post.url }}"><font size="5"> {{ post.title }}  </font></a> 
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>