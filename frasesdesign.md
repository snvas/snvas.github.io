---
layout: page
title: Coletânia de Frases
permalink: /frasestodas/
order: 6
---

{% assign frases_online = site.data.frases %}

{% for item in frases_online %}
<h3 class="post-title">{{ item.Frase }}</h3>
<h5>{{ item.Autor}}</h5>
 <hr/>
{% endfor %}
