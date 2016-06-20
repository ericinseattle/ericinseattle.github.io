---
layout: page
title: "Projects"
description: ""
group: navigation
---
{% include JB/setup %}

{% for post in site.categories.project %}
    <li>{{ post.title }}</li>
{% endfor %}