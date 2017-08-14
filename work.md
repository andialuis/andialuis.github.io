---
layout: default
title: all projects
permalink: /work/
---

<article class="site-section site-section-last">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
  </header>

    <ul class="project-list">
      {% for project in site.categories['project'] reversed limit:3 %}
        {% include project.html %}
      {% endfor %}
    </ul>


</article>