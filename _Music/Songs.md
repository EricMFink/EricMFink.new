---
layout: song-list
permalink: /Songs/
title: Songs
---

<ul>
{% for song in site.data.songs %}
<a href="{{ site.baseurl }}/Music/{{ song.playlist }}/{{ song.file }}">
<li>{{ song.title }}</li>
</a>
{% endfor %}
</ul>