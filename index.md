---
layout: default
title: Home
---

Welcome to my blog!

Here are my recent posts:

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}