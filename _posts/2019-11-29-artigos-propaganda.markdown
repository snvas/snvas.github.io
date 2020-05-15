---
layout: post
title:  "Artigos sobre Propaganda"
date:   2019-11-29 18:55:36 -0300
author:  Soraia Novaes
tags: 
 - artigos 
---

<p>Coleç?o de artigos cientí­ficos garimpados na web ao longo dos anos de estudo sobre o tema Propaganda.</p>

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Propaganda"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      
