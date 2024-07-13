---
layout: page
permalink: /music/
title: Music
---

### [Tired & Hungry & Looking For My Youth](https://www.emfink.net/Tired&Hungry)

![](Tired&Hungry.png)

<ul>
{% for song in site.data.songs.Tired&Hungry %}<li><a href="./{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

### [A Promise With A Catch]({{ site.baseurl }}](https://www.emfink.net/PromiseWithACatch)

![](Promise.png)

<ul>
{% for song in site.data.songs.Promise %}<li><a href="./{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

### [Revolutionary Anthems, Labor Hymns, & Sectarian Satire](https://www.emfink.net/RevolutionaryAnthems)

![](RevolutionaryBallads.png)

<ul>
{% for song in site.data.songs.RevolutionaryBallads %}<li><a href="./{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

