---
layout: archive
permalink: /
title: "Welcome to My Bat Mitzvah Project Website!"
image: featured-img.jpg
---

<div class="page-lead">
	<img src="/MirasBatMitzvah/images/banner-1600x480.jpeg">
	<!-- <img src="/images/banner-1600x480.jpeg"> -->
	<!-- <div class="wrap page-lead-content">
        <h1>Mira's Bat Mitzvah Fundraiser</h1>
        <h2>Make a difference to kids with congenital heart defects.</h2>
    </div>-->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
