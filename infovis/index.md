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

- https://public.tableau.com/views/4_540/1?:embed=y&:display_count=yes&publish=yes![仪表板](https://i.loli.net/2018/01/07/5a520247be06a.png)


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出來-->