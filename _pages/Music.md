---
layout: page
permalink: /Music/
title: Playlists
---

## Playlists

[Tired & Hungry & Looking For My Youth](https://www.emfink.net/Tired&Hungry.html)

[A Promise With A Catch]([{{ site.baseurl }}](https://www.emfink.net/PromiseWithACatch)

[Revolutionary Anthems, Labor Hymns, & Sectarian Satire(https://www.emfink.net/RevolutionaryAnthems)

## Songs

{% for song in site.songs %}<ul><li><a href="https://www.emfink.net/songs/{{ song.url }}">{{ song.title }}</a></li></ul>{% endfor %}