---
layout: default
title: Blog
---

Blog
===========

<ul>
	{% assign excerptControl = 0 %}
	{% for post in site.posts %}
    <li>
        [{{post.date | date: "%x" }}] <a href="{{ post.url }}"><font size="5"> {{ post.title }}  </font></a> 
        {% if excerptControl < 3 %} 
        	{{ post.excerpt }}
        {% endif %}
        {% assign excerptControl = excerptControl | plus: 1 %}
    </li>
    {% endfor %}
</ul>