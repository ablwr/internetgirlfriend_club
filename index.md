---
layout: default
title: Internet Girlfriend Club
navigation: false
---

<div class="showcase-header center">🐴 Volume 5 🐴</div>
<div class="showcase center">
  {% for post in site.volume5 %}
    <div class="showcase-item"><a href="{{ post.url }}">{{ post.chapter }}</a></div>
  {% endfor %}
</div>
