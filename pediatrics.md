---
layout: page
title: Pediatrics
---

<article class="page">
  {% for study in site.pediatrics %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="post box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</article>
