---
layout: page
title: "Projects"
description: ""
group: navigation
---
{% include JB/setup %}

{% for post in site.categories.project %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

