---
layout: default
title: Meus posts
permalink: /posts/
---

<h1 class='godOfWarFont'> Posts</h1>

### Aqui estão todos os posts publicados até agora:

<br/>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>
