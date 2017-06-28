---
layout: default
title: Events
---

# Courses

<ul class="list_post">
    {% for post in site.posts %}
    {% if post.category contains 'course' %}
  <li><a class="button_post" href="{{ post.url }}">{{ post.title }} </a></li>
    {% endif %}
  {% endfor %}
</ul>
