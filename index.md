---
title: Anant Shiva
description: 
layout: default
---

{: .large}
This is a fucking blog, and it's wonderful. It's perfect. It allows you to share your words, in your own voice, with no corporate fuckery to fuck it up for you.

Blogs are very fucking important, because they allow you to own your content. Whatever you share, it's yours and no fucks, like Elon Fucking Musk, can take that away from you.

They can't ban you from your own blog. They can't silence you. They can't make money from you. Fuck them.

Own your content; **start a fucking blog.**


{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
    <p class="meta">{{ post.description }}</p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}

