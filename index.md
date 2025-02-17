---
layout: default
title: Hello
---

## Hi, I'm Anant.

**Stop worrying about the style, focus on your writing.**

- Looks great on *any* device
- Tiny, optimized, and awesome pages
- No trackers, ads, or scripts, *did I mention minimal already?*
- Auto light and dark themes
- Tag support, to filter blog pages
- Quick, *15 minute* setup
- Gallery view for your images
- Code highlighting

## Recent Posts

{% for post in site.posts limit:3 %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}