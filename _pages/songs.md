---
layout: page
permalink: /Songs/
title: Songs
---

<img src='https://www.emfink.net/assets/img/tired.png' alt='Tired & Hungry & Looking for My Youth' width='300' height='300'>

<ul>
{% for song in site.data.songs %}
	<a href="../Songs/{{ song.file }}">
		<li>{{ song.title }}</li>
	</a>
{% endfor %}
</ul>
