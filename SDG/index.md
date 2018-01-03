---
layout: archive
title: "信息可视化作品集"
date: 2018-01-03
modified:
excerpt: "让人有密集恐惧症的地图"
tags: []
image: 
  feature: milu-two.gif
  teaser:
---

在此展示作品

<div class="tiles">
{% for post in site.categories.SDG %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 SDG 的列出来-->