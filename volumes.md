---
layout: page
title: Volumes
permalink: /volumes/
navigation: true
---

<ul>
  <li><a class="page-link" href="/volume1/0.html">Volume 1</a></li>

  <ul class="">
    {% for post in site.volume1 %}
      <li class=""><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <li><a class="page-link" href="/volume2/0.html">Volume 2</a></li>

  <ul class="">
    {% for post in site.volume2 %}
      <li class=""><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <li><a class="page-link" href="/volume3/0.html">Volume 3</a></li>

  <ul class="">
    {% for post in site.volume3 %}
      <li class=""><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <li><a class="page-link" href="/volume3/0.html">Volume 4</a></li>
  <ul class="">
    {% for post in site.volume4 %}
      <li class=""><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</ul>
