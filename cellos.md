---
title: Cellos
layout: category
---

{% assign cellos = site.products | where: "category", "cellos" %}

{% for cello in cellos %}
    {{ cello.title }}
{%endfor%}
