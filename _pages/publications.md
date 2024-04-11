---
layout: page
permalink: /publications/
title: publications
description: Select journal publications in inverse chronological order. If you have trouble accessing any papers related to my work or that of my lab members feel free to email me directly.
years: [2024, 2022, 2020, 2018, 2016, 2015]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
