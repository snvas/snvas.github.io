---
layout: post
title:  "Cursos de Química Online e Gratuitos"
date:   2019-11-20 18:55:36 -0300
author: soraia
tags: 
 - cursos online
 - áreas de cursos
---

## Confira os cursos garimpados na web da área de Química.

 {% assign curso_online = site.data.cursosninja | where: "Categoria","Química" | sort: 'nome'  %}

{% for curso in curso_online %}
<h1 class="post-title">{{ curso.nome }} - {{ curso.tempo}} h/a</h1>

<p>Pré-requisito: {{ curso.prerequisito}}</p>

<h5>Investimento: {{ curso.investimento}}</h5>
<h3>{{ curso.Complemento}}</h3>
<hr>

 {% endfor %}      
