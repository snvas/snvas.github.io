---
layout: post
title:  "Artigos sobre Gestão de Negócios"
author:  Soraia Novaes
tags: 
 - artigos 
---

<p>Coleção de artigos científicos garimpados na web ao longo dos anos de estudo sobre o tema Gestão de Negócios.</p>

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Gestão de Negócios"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      
