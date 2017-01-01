---
layout: page
title: Tags
permalink: /tags/
---

<ul>
{% for tags in page.posts %}
  <li>Tags: {{ post | tags }}</li>
{% endfor %}
</ul>

<div id="tag-cloud">
  {{ site | tag_cloud }}
</div>