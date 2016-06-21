---
layout: page
title: "Projects"
description: ""
group: navigation
---
{% include JB/setup %}

{% for post in site.categories.project %}
<h2><li><a href="{{ post.url }}">{{ post.title }}</a></li></h2>
{% endfor %}
<br/>