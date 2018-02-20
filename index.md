---
layout: archive
permalink: /
title: "Welcome to My Bat Mitzvah Site!"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
