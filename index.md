---
layout: page
title: 高等数学题库
tagline:
---
<ul>
<h3>
<a href="https://github.com/cnumathliu/cnumathliu.github.io/tree/master/assets" target="_blank">全部文件</a>
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
