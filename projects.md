---
layout: page
title: "Projects"
description: ""
group: navigation
---
{% include JB/setup %}

{% for category in site.categories = "project" %} 
  <ul>
    {% assign pages_list = category[1] %}  
    {% include JB/pages_list %}
  </ul>
{% endfor %}