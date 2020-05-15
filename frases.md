---
layout: page
title: Frases
permalink: /frases/
order: 6
---
<br>
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

{% assign frases_online = site.data.frases %}

{% for item in frases_online %}
<h3 class="post-title">{{ item.Frase }}</h3>
<h5>{{ item.Autor}}</h5>
 <hr/>
{% endfor %}
