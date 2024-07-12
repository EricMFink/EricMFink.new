---
layout: page
permalink: /Music/
title: Playlists
---

## Playlists

[![Tired & Hungry & Looking For My Youth]({{ site.baseurl }}/assets/mp3/tired.png)]({{ site.baseurl }}/Tired&Hungry.html)

[![A Promise With A Catch]({{ site.baseurl }}/assets/mp3/promise.png)]({{ site.baseurl }}/PromiseWithACatch.html)

[![Revolutionary Anthems, Labor Hymns, & Sectarian Satire]({{ site.baseurl }}/assets/mp3/revolution.png)]({{ site.baseurl }}/RevolutionaryAnthems.html)

## Songs

{% for song in site.songs %}<ul><li><a href="{{ site.baseurl }}/songs/{{ song.url }}>{{ song.title }}</a></li></ul>{% endfor %}