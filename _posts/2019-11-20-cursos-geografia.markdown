---
layout: post
title:  "Cursos de Geografia Online e Gratuitos"
date:   2019-11-20 18:55:36 -0300
author: soraia
tags: 
 - cursos online
 - áreas de cursos
---

<div id="fiap"></div>

 {% assign curso_online = site.data.cursosninja | where: "Categoria","Geografia" | sort: 'nome'  %}

{% for curso in curso_online %}
<h1 class="post-title">{{ curso.nome }} - {{ curso.tempo}} h/a</h1>

<p>Pré-requisito: {{ curso.prerequisito}}</p>

<h5>Investimento: {{ curso.investimento}}</h5>
<h3>{{ curso.Complemento}}</h3>
<hr>

 {% endfor %}      
