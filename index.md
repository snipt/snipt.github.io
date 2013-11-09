---
layout: page
title: JavaScript tutorial
tagline: Supporting tagline
---
{% include JB/setup %}

## Welcome

Code References for Front-end Web Development.
    
It is a collection of quick reference guide for assisting development.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
