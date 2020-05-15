---
layout: page
title: Cursos Online
permalink: /cursos/
order: 1
---
 <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- codecamp -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-3011890130990408"
     data-ad-slot="9846490006"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>

### Confira os cursos online da EmpreendeLab

{% assign curso_online = site.data.cursosonline  | where: "categoria","Online" | sort: 'nome'  %}

{% for curso in curso_online %}
<p>{{ curso.imagem}}</p>
<h1 class="post-title">{{ curso.nome }} </h1>

<p>{{ curso.descricao}}</p>

<h5>{{ curso.inscrevase}}</h5>

<hr>
 {% endfor %}