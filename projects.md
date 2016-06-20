---
layout: page
title: "Projects"
description: ""
group: navigation
---
{% include JB/setup %}

{% for post in site.categories.project %}
  <ul>
    {% include JB/pages_list %}
  </ul>
{% endfor %}
