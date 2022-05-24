---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order.
last_modified_at:   2022-05-24 21:00:00 +0000
years: [2022, 2021, 2014, 2013, 2012, 2011, 2010, 2008]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
