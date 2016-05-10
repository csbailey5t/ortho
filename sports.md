---
layout: page
title: Sports
---

<div>
  {% for study in site.sports %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</div>
