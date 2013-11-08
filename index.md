---
layout: page
title: arbel的博客
tagline: 记录点滴
---
{% include JB/setup %}

## 目录

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 简介

来自合肥工业大学(Hefei University of Technology)

