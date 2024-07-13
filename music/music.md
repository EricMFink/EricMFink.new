---
layout: page
permalink: /music/
title: Music
---

##### [Tired & Hungry & Looking For My Youth]({{ site.baseurl}}/music/TiredAndHungry)

<a href="{{ site.baseurl}}/music/RevolutionaryAnthems"><img src="{{ site.baseurl}}/assets/music/RevolutionaryAnthems/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.TiredAndHungry %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

##### [A Promise With A Catch]({{ site.baseurl}}/music/PromiseWithACatch)

<a href="{{ site.baseurl}}/music/Promise"><img src="{{ site.baseurl}}/assets/music/Promise/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.Promise %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

##### [Revolutionary Ballads, Labor Hymns, & Sectarian Satire]({{ site.baseurl}}/music/RevolutionaryBallads)

<a href="{{ site.baseurl}}/music/RevolutionaryBallads"><img src="{{ site.baseurl}}/assets/music/RevolutionaryBallads/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.RevolutionaryBallads %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

