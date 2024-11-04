---
layout: default
title: Welcome to Shelby's Blog
---

## About Me

Welcome to my blog! Here, I'll share insights and thoughts on technology, embedded systems, Linux, and more.

## Latest Posts

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
