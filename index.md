---
layout: archive
permalink: /
title: "Welcome to My Bat Mitzvah Project Website!"
image: featured-img.jpg
---

<div class="page-lead">
	<img src="/images/banner-fact-1600-720-face.jpg">	
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->


