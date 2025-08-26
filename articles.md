---
layout: default
title: 記事一覧
permalink: /blog/
---

<h1>{{ page.title }}</h1>

<ul>
  {% for post in site.blog %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>