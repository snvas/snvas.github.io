---
layout: post
title:  Artigos sobre Propaganda
author:  Soraia Novaes
tags: 
 - artigos 
---

<p>Artigos garimpados na web ao longo dos anos de estudo sobre o tema Propaganda.</p>

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Propaganda"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      
