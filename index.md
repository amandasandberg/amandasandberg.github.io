---
layout: default
title: "Amanda Sandberg"
---

<div style="position: absolute; right: -220px; width: 200px;">
<img src="jag.png" width="100%" />

<h3 style="clear: both;">Rubrik</h3>
<dl>
{% for post in site.posts %}	
<dt><small>{{ post.date | date: "%Y-%m-%d" }}</small></dt><dd><a href="{{ post.url }}">{{ post.title }}</a></dd>
{% endfor %} 
</dl>
</div>

<div style="position: absolute; left: -220px; width: 200px;">
<q lang="ru">Ничего я не хочу, ничего мне не нужно, никого я не люблю... </q> A. Tjechov
</div>

<div style="margin-top: 10em;" />

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
