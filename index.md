---
layout: home
title: Home
---

# Welcome to my blog!

Here are my latest updates:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %d, %Y" }})
{% endfor %}
