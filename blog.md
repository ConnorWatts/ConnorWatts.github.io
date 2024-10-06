---
layout: default
title: Blog
---

# Blog

Here are my latest blog posts:

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}
