---
layout: default
title: Internet Girlfriend Club
navigation: false
---

<div class="showcase-header center">🙆 Volume 6 🙆</div>
<div class="showcase center">
  {% for post in site.volume6 %}
    <div class="showcase-item"><a href="{{ post.url }}">{{ post.chapter }}</a></div>
  {% endfor %}
</div>
