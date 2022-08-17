---
layout: page
title: General
---

{% for  item in site.posts %}
{% if item.category =="general" %}
<p> {{ item.date | date: "%d %b, %Y" }}: <a href="{{item.url}}" > {{ item.title }} </a> 
</p>
{% endif %}
{% endfor %}
