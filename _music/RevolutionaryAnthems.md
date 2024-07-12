---
layout: amplitudejs
title: Revolutionary Anthems, Labor Hymns, & Sectarian Satire

---

    {% for song in site.data.revolution %}{
    "name": "{{ song.title }}",
	"album": "{{ song.album }}",
    "url": "/{{ song.playlist }}/{{ song.file }}.mp3",
    "cover_art_url": "../img/{{ song.playlist }}.png"
    },{% endfor %}