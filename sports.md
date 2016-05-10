---
layout: page
title: Sports
---

<article class="page">
  {% for study in site.sports %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="post box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</article>
