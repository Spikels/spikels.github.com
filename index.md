---
layout: page
title: "Spikels' Sauce"
tagline: 
---
{% include JB/setup %}

## Random Thoughts and Notes

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
