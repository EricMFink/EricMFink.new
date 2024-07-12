---
layout: amplitudejs
title: Tired & Hungry & Looking For My Youth 

---

    {% for song in site.data.tired %}{
    "name": "{{ song.title }}",
	"album": "{{ song.album }}",
    "url": "/{{ song.playlist }}/{{ song.file }}.mp3",
    "cover_art_url": "../img/{{ song.playlist }}.png"
    },{% endfor %}