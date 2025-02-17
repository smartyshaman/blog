---
layout: default
title: Hello
---

Currently living in Cape Town — possibly the most beautiful city in the world.
I'm the creator of the no-nonsense blogging platform, Bear, and a few other things.
I also write short-to-mid length essays about life, tech, and whatever I currently find interesting.

### Recent Posts
{% for post in site.posts limit:5 %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}