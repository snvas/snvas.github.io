---
layout: page
title: Frases
permalink: /frases/
order: 5
---

{% assign frases_online = site.data.frases  | where: "Categoria","Design"| sort: 'Frase'  %}

{% for frase in frases_online %}
<h2 class="post-title">{{ frase.Frase }}</h2>
<h3>{{ frase.autor}}</h3>

{% endfor %}