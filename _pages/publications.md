---
layout: page
permalink: /Publications/
title: Publications

---

<ul>
{% for publication in site.data.publications %}
	<li>{{ publication.author }}{% if publication.coauthor %} & {{ publication.coauthor }}{% endif %}, <a href="https://www.emfink.net/assets/pdf/{{ publication.pdf }}">{{ publication.title }}</a>, {{ publication.volume }} {{ publication.container-title }} {{ publication.page1 }} ({{ publication.date }})</li>
{% endfor %}
</ul>
