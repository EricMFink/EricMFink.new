---
layout: song-list
title: Songs
---

<ul>
{% for song in site.data.songs %}
<a href="{{ site.baseurl }}/assets/mp3/{{ song.playlist }}/{{ song.file }}.mp3">
<li>{{ site.baseurl }}/Music{{ song.title }}</li>
</a>
{% endfor %}
</ul>