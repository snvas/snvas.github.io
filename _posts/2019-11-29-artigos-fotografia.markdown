---
layout: post
title:  "Artigos sobre Fotografia"
date:   2019-11-29 18:55:36 -0300
author: soraia
tags: 
 - artigos 
---
<p>Coleção de artigos científicos garimpados na web ao longo dos anos de estudo sobre o tema Fotografia e Psicologia.</p>

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Fotografia"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      


### Psicologia

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Psicologia"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}  