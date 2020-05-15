---
layout: page
title: Frases
permalink: /frases/
order: 5
---
<br>

{% assign frases_online = site.data.frases %}

{% for item in frases_online %}
<h3 class="post-title">{{ item.Frase }}</h3>
<h5>{{ item.Autor}}</h5>
 <hr/>
{% endfor %}
