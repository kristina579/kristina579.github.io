---
layout: archive
title: "信息可视化作品集"
date: 2018-01-03
modified:
excerpt: "展示这学期的信息可视化作品"
tags: []
image: 
  feature: 
  teaser:
---



<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出來-->