---
layout: page
title: Adult Recon
---

<article class="page">
  {% for study in site.recon %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="post box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</article>
