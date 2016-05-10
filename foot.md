---
layout: page
title: Foot & Ankle
type: foot
---

<div>
  {% for study in site.foot %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</div>
