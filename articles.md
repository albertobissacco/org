---
layout: page
title: Articles
permalink: /articles/
---

<article class="container">
{% for album in site.articles limit:0 %}
      <li>
        <a href="{{ album.url }}">{{ album.title }}</a>
        <p>{{ album.short-description }}</p>
      </li>
{% endfor %}
</article>
