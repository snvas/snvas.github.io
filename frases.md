---
layout: page
title: Reflexões sobre Tecnologia
permalink: /frases/
order: 6
---


### [Todas as Frases](/frasestodas/)

{% assign frases_online = site.data.frases | where: "Categoria","Tecnologia" | sort: 'Autor' %}

{% for item in frases_online %}
<h3 class="post-title">{{ item.Frase }}</h3>
<h5>{{ item.Autor}}</h5>
 <hr/>
{% endfor %}
