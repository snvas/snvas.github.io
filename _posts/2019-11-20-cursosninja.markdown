---
layout: post
title:  "Cursos Ninja"
date:   2019-11-20 18:55:36 -0300
author: soraia
---

<div id="fiap"></div>

 {% assign curso = site.data.cursosninja | where: "categoria","Tecnologia da Informação" %}

{% for curso in site.data.cursosninja %}
<h1 class="post-title">{{ curso.nome }}</h1>

<h4>Pré-requisito: {{ curso.prerequisito}}</h4>
<h4>Carga Horária: {{ curso.tempo}}</h4>
<h4>Investimento: {{ curso.investimento}}</h4>
<h2>{{ curso.Complemento}}</h2>
<h2>{{ curso.categoria}}</h2>

 {% endfor %}      