---
layout: default
title: "Amanda Sandberg"
---

<div style="position: absolute; right: -220px; width: 200px;">
<img src="jag.png" />

<h3 style="clear: both;">Rubrik</h3>
<dl>
{% for post in site.posts %}	
<dt><small>{{ post.date | date: "%Y-%m-%d" }}</small></dt><dd><a href="{{ post.url }}">{{ post.title }}</a></dd>
{% endfor %} 
</dl>
</div>

<div style="position: absolute; left: -220px; width: 200px;">
<q lang="ru">Ничего я не хочу, ничего мне не нужно, никого я не люблю... </q><br/><small>A. Tjechov</small>
</div>

<div style="margin-top: 10em;" />

{% assign post = site.posts.first %}
{{ post.content }}
