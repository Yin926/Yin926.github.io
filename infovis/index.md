---
layout: archive
title: "可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: 
  teaser:
---

<img src="/images/高德地图-琴行.png" height="600" width="600" />
<div><a href="https://public.tableau.com/views/_18368/3?:embed=y&:display_count=yes&publish=yes"></a></div>
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->