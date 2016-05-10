---
layout: page
title: Adult Recon
---

<div>
  {% for study in site.recon %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</div>
