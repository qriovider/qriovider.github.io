---
layout: page
permalink: /publications/
title: publications
description: Under preparation
years: [2022, 2023]
nav: true
nav_order: 1
---

## presentations in international conference

## domestic conferences (non-reviewed)

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
