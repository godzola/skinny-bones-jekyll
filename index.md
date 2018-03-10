---
layout: archive
permalink: /
title: "Welcome to My Bat Mitzvah Project Website!"
image: featured-img.jpg
---

<div class="page-lead">
	<img src="/images/banner-green-1600x480.jpeg">
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
