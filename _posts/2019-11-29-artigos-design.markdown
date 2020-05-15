---
layout: post
title:  "Artigos sobre Design"
author:  Soraia Novaes
tags: 
 - artigos 
---
<p>Coleção de artigos científicos garimpados na web ao longo dos anos de estudo sobre o tema Design.</p>

### Design de Produto

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Design de Produto"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      


### Design Gráfico

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Design Gráfico"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}      


### Design de Serviços

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Design de Serviços"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}  
 
### Design Urbano

 {% assign artigo_online = site.data.artigos  | where: "Categoria","Design Urbano"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %} 

 ### Web Design
 {% assign artigo_online = site.data.artigos  | where: "Categoria","Web Design"| sort: 'Nome'  %}

{% for artigo in artigo_online %}
<h1 class="post-title">{{ artigo.Nome }}</h1>

<h3><a href="{{ artigo.url}}">{{ artigo.Formato}}</a></h3>


<hr>

 {% endfor %}     