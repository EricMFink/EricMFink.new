---
layout: amplitudejs
permalink: /Revolutionary Anthems/
title: Revolutionary Anthems, Labor Hymns, & Sectarian Satire

---

{% for song in site.data.revolution %}{"name": "{{ song.title }}","album": "{{ song.album }}","url": "{{ site.baseurl }}/assets/mp3/{{ song.playlist }}/{{ song.file }}.mp3","cover_art_url": "{{ site.baseurl }}/assets/mp3/{{ song.playlist }}.png"},{% endfor %}