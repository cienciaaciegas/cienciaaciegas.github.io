---
layout: page
title: Software
---

{% for  item in site.posts %}
{% if item.category =="software" %}
<p> {{ item.date  }}: <a href="{{item.url}}" > {{ item.title }} </a> 
</p>
{% endif %}
{% endfor %}
