---
layout: category  # Ensure there is a layout named 'category' in your _layouts directory
title: Basketball
permalink: /basketball/
---

[Add any static content here that you want to always appear above the posts list]

{% for post in site.categories.basketball %}
  <div class="post">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
