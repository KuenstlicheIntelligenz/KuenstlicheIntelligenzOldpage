---
layout: post
title:  "Welcome to Jekyll!"
categories: [AI, DeepLearning]
tags: [start]
---

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

# Welcome

**Hello world**, this is my first Jekyll blog post.

I hope you like it!

![AIbab](/assets/aibab.png)
