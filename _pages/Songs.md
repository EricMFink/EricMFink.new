---
layout: page
title: Songs & Playlists
---

<ul>
{% for item in site.music %}
<li><a href="{{ site.baseurl }}/music/{{ item.url }}>{{ item.title }}</a></li>
{% endfor %}
</ul>