---
layout: page
title: Software
---

{% for  item in site.posts %}
{% if item.category =="software" %}
<p> {{ item.date | date: "%d %b, %Y" }}: <a href="{{item.url}}" > {{ item.title }} </a> 
</p>
{% endif %}
{% endfor %}
