---
layout: default
title: Events
---

# Events and courses

<ul class="list_post">
    {% for post in site.posts %}
  <li><a class="button_post" href="{{ post.url }}">{{ post.title }} </a></li>
  {% endfor %}
</ul>
