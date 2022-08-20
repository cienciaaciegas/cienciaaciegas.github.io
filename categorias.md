---
layout: page
permalink: /categorias/
title: "Categorías"
---

{% assign contador = 0 %}
{% for post in site.posts %}
{% assign contador = contador | plus:1 %}
{% endfor %}
{% if contador != 1 %}
<p>{{ contador }} artículos publicados en total</p>
{% else %}
<p>{{ contador }} artículo publicado en total</p
{% endif %}




{% for item in site.categorias %}
{% assign contador=0 %}
{% for post in site.posts %}
{% if post.category == item.category %}
{% assign contador = contador | plus:1 %}
{% endif %}
{% endfor %}
<p><a href="{{ item.url }}">{{ item.title }} ({{ contador }})</a></p>
{% endfor %}
