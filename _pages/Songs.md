---
layout: page
title: Songs & Playlists
---

{% for item in site.music %}
<ul>
<li><a href="{{ site.baseurl }}/music/{{ item.url }}>{{ item.title }}</a></li>
</ul>
{% endfor %}