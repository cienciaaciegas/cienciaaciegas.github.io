---
layout: page
title: Apuntes
---

{% for  item in site.posts %}
{% if item.category =="apuntes" %}
<p> {{ item.date  }}: <a href="{{item.url}}" > {{ item.title }} </a> 
</p>
{% endif %}
{% endfor %}