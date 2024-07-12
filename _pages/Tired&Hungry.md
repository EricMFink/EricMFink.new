---
layout: amplitudejs
permalink: /Tired&Hungry/
title: Tired & Hungry & Looking For My Youth 

---

{% for song in site.data.tired %}{"name": "{{ song.title }}","album": "{{ song.album }}","url": "{{ site.baseurl }}/assets/mp3/{{ song.playlist }}/{{ song.file }}.mp3","cover_art_url": "{{ site.baseurl }}/assets/mp3/{{ song.playlist }}.png"},{% endfor %}