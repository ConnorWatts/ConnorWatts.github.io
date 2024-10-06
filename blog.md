---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Here are my latest blog posts:

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}
