---
layout: page
permalink: /publications/
title: publications
description: UNDER CONSTRUCTION
years: [1967, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---


<h1>UNDER CONSTRUCTION</h1>

below is sample.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
