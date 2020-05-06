---
layout: page
title: Cursos Online
permalink: /cursos/
order: 1
---

### Confira os cursos online da EmpreendeLab

{% assign curso_online = site.data.cursosonline  | where: "categoria","Online" | sort: 'nome'  %}

{% for curso in curso_online %}
<p>{{ curso.imagem}}</p>
<h1 class="post-title">{{ curso.nome }} </h1>

<p>{{ curso.descricao}}</p>

<h5>{{ curso.inscrevase}}</h5>

<hr>
 {% endfor %}      

