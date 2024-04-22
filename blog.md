---
layout: default
title: Blog
---
<h2>Latest posts</h2>

<ul>
  {% for post in site.posts %}
  <li>
    <h3><a href="{{post.url}}">{{post.title}}</a></h3>
  </li>
  {% endfor %}
</ul>