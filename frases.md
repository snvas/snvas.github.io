---
layout: page
title: Frases
permalink: /frases/
order: 5
---
<br>

{% assign frases_online = site.data.frases  | where: "Categoria","Design"| sort: 'Frase'  %}

{% for item in frases_online %}
<h2 class="post-title">{{ item.Frase }}</h2>
<h3>{{ item.autor}}</h3>
 <hr/>
{% endfor %}
