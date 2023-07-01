---
title: Anant Shiva
description: 
layout: default
---

{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
    <p class="meta">{{ post.description }}</p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}

