---
layout: page
permalink: /music/
title: Music
---

#### [Tired & Hungry & Looking For My Youth]({{ site.baseurl}}/music/TiredAndHungry)

<a href="{{ site.baseurl}}/music/TiredAndHungry"><img src="{{ site.baseurl}}/assets/music/TiredAndHungry/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.TiredAndHungry %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

#### [A Promise With A Catch]({{ site.baseurl}}/music/PromiseWithACatch)

<a href="{{ site.baseurl}}/music/PromiseWithACatch"><img src="{{ site.baseurl}}/assets/music/PromiseWithACatch/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.PromiseWithACatch %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

#### [Revolutionary Ballads, Labor Hymns, & Sectarian Satire]({{ site.baseurl}}/music/RevolutionaryBallads)

<a href="{{ site.baseurl}}/music/RevolutionaryBallads"><img src="{{ site.baseurl}}/assets/music/RevolutionaryBallads/cover.png" alt="" width="320"/></a>

<ul>
{% for song in site.data.songs.RevolutionaryBallads %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

