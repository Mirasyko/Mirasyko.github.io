---
layout: default
title: "Academic Notes"
permalink: /pages/academic/
---


# Academic Notes


<div class="list">
{% assign items = site.academic | sort: 'date' | reverse %}
{% for post in items %}
<article class="item">
<h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
<div class="meta">{{ post.date | date: "%B %e, %Y" }}{% if post.tags %} · {{ post.tags | join: ', ' }}{% endif %}</div>
{% if post.excerpt %}<p>{{ post.excerpt | strip_html }}</p>{% endif %}
</article>
{% endfor %}
</div>