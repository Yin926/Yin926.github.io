---
layout: archive
title: "可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "加油加油"
tags: []
image: 
  feature: notes.gif
  teaser:
---


<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->