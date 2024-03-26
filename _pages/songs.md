---
layout: page
permalink: /Songs/
title: Songs
---

<ul>
{% for song in site.data.songs %}
	<a href="../Songs/{{ song.file }}">
		<li>{{ song.title }}</li>
	</a>
{% endfor %}
</ul>
