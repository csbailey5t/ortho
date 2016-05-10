---
layout: page
title: Hand
---

<article class="page">
  {% for study in site.hand %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="post box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</article>
