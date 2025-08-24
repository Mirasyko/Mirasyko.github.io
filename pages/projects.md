---
layout: default
title: "Projects"
permalink: /pages/projects/
---


# Projects


<div class="list">
{% assign items = site.projects | sort: 'date' | reverse %}
{% for post in items %}
<article class="item">
<h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
<div class="meta">{{ post.date | date: "%B %e, %Y" }}{% if post.tech %} · Tech: {{ post.tech | join: ', ' }}{% endif %}</div>
{% if post.summary %}<p>{{ post.summary }}</p>{% endif %}
</article>
{% endfor %}
</div>