

{% assign frase_online = site.data.frases  | where: "Categoria","Design"| sort: 'Frase'  %}

{% for frase in frase_online %}
<h2 class="post-title">{{ frase.Frase }}</h2>
<h3>{{ frase.autor}}</h3>
 
{% endfor %}


{% assign sorted_categorias = site.data.frases | sort %}
{% for categoria in sorted_categorias %}
  {% assign c = categoria | first %}
  {% assign frases = categoria | last %}
 
    <a href onclick="filter('{{ c }}'); return false;" style="font-size: large;">{{ c }}</a>&nbsp;&nbsp;&nbsp;
 
{% endfor %}

{% for categoria in site.data.frases %}
{% assign c = categoria | first %}
{% assign frases = categoria | last %}
<div class="blog-list-container hidden" id="{{ t }}-container">
  <div class="list-item">
    <p>&nbsp;</p>
    {% for frases in site.data.frases %}
      {% if frases.tags contains c %}
        <h3 class="list-post-title">
          {{ frase.Frase }}<br><br>
        </h3>
      {% endif %}
    {% endfor %}
  </div>
