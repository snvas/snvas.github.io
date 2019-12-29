---
layout: post
title:  "Cursos Ninja"
date:   2019-11-20 18:55:36 -0300
author: soraia
---

<div id="fiap"></div>
 {% for curso in site.data.cursosninja %}

<h1 class="post-title">{{ curso.nome }}</h1>
<h2 class="post-title">{{ curso.prerequisito}}</h1>
<h2 class="post-title">{{ curso.complemento}}</h1>

 {% endfor %}      