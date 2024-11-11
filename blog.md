---
layout: default
title: Blog
permalink: /blog/
command: "cywarrior@det520:~/blog$ ls"
---

# Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
