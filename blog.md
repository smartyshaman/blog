---
layout: default
title: Blog
description: This is a fucking blog page. Enjoy it. Boo.
permalink: /blog/
---

{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
    <p class="meta">{{ post.description }}</p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}
