---
layout: page
permalink: /research/
title: Research
# description: publications by categories in reversed chronological order.
# years: [1967, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---
<div class="publications">
<h2 class="publications">Working Papers</h2>
{% bibliography -f working_papers -q @** %}
</div>

<!-- _pages/publications.md -->
<div class="publications">
<h2 class="publications">Publications</h2>
{% bibliography -f publications -q @** %}

<!-- {%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %} -->

</div>
