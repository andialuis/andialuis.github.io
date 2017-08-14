---
layout: default
title: all projects
permalink: /articles/
---

<article class="site-section site-section-last">
	<header class="post-header">
		<h1 class="post-title">{{ page.title }}</h1>
	</header>

	<ul class="post-list">
	{% for post in site.categories['blog'] reversed %}
	<li>
	{% include post2.html %}
	{% endfor %}
	</li>
	</ul>


</article>