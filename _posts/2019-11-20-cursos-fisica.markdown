---
layout: post
title:  "Cursos de Física Online e Gratuito"
author:  Soraia Novaes
tags: 
 - cursos online
 - áreas de cursos
---


## Confira os cursos garimpados na web da área de Física.

 {% assign curso_online = site.data.cursosninja | where: "Categoria","Física" | sort: 'nome'  %}

{% for curso in curso_online %}
<h1 class="post-title">{{ curso.nome }} - {{ curso.tempo}} h/a</h1>

<p>Pré-requisito: {{ curso.prerequisito}}</p>

<h5>Investimento: {{ curso.investimento}}</h5>
<h3>{{ curso.Complemento}}</h3>
<hr>

 {% endfor %}      
