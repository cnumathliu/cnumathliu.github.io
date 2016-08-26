---
layout: page
title: zdwchang
tagline: Ride My Phaedrus
---
<ul>
<h3>
<a href="http://github.zdwchang.com" target="_blank">My GitHub</a>
</h3>
<br>
{% for post in site.posts %}
<b>{{ post.date | date_to_long_string }}</b>
<br>
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<br>
<br>
{{ post.content}}
<br>
<hr>
{% endfor %}
</ul>
