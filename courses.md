---
layout: default
title: Events
---

# Courses

## Past and upcoming courses

<ul class="list_post">
    {% for post in site.posts %}
    {% if post.category contains 'course' %}
  <li><a class="button_post" href="{{ post.url }}">{{ post.title }} </a></li>
    {% endif %}
  {% endfor %}
</ul>

## What attendees are saying

“I think this is one of the best workshops I have been to in terms of achieving the set goals. I now have the ability to start chasing stats in R."

“Prior to doing the R workshop, I had no experience with programming or writing code. This workshop was a great introduction into the world of R and since then my skills in R and writing code have grown exponentially... R is now the only statistical package that I use for all of my research.”

"The whole course was excellent! Well organised, great notes. The informal style made it easy to ask questions. Will definitely recommend to others."

"As a complete newbie to R, and having just had a panic attack last week about needing to run CART and Random Forest with little know-how, this was a phenomenal workshop. I feel like I have a much better grasp of the program and its coding language, and am much more confident that I'll be able to adeptly run my analyses. ... brought me back from the brink of quitting my PhD!”
