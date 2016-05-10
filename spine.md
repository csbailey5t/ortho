---
layout: page
title: Spine
---

<div>
  {% for study in site.spine %}
  <a href="{{ site.baseurl }}{{ study.url }}">
    <article class="box">
      <h2 class="post-title">
          {{ study.title }}
      </h2>
    </article>
  </a>
  {% endfor %}
</div>
