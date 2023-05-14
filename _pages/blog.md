---
layout: page
title: Blog
include_in_header: true
---

<h1>Blog</h1>

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}