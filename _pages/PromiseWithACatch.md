---
layout: amplitudejs
permalink: /PromiseWithACatch/
title: A Promise With a Catch

---

{% for song in site.data.promise %}{"name": "{{ song.title }}","album": "{{ song.album }}","url": "/{{ song.playlist }}/{{ song.file }}.mp3","cover_art_url": "{{ site.baseurl }}/assets/img/{{ song.playlist }}.png"},{% endfor %}