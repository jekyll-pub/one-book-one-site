---
layout: default
title: 创作随笔
nav_order: 7
---

# 『创作随笔』

以笔记形式记录创作历程，这一部分利用了 Jekyll 最原始的记日志功能。

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
