---
layout: page
permalink: /categorias/
title: "Categorías"
---

{% for item in site.categorias %}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}
