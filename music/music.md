---
layout: page
permalink: /music/
title: Music
---

### [Tired & Hungry & Looking For My Youth]({{ site.baseurl}}/music/Tired&Hungry)

![](Tired&Hungry.png)

<ul>
{% for song in site.data.songs.Tired&Hungry %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

### [A Promise With A Catch]({{ site.baseurl}}/music/PromiseWithACatch)

![](Promise.png)

<ul>
{% for song in site.data.songs.Promise %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

### [Revolutionary Anthems, Labor Hymns, & Sectarian Satire]({{ site.baseurl}}/music/RevolutionaryAnthems)

![](RevolutionaryBallads.png)

<ul>
{% for song in site.data.songs.RevolutionaryBallads %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

