---
layout: page
permalink: /publications/
title: publications
description: Under preparation
years: [2022, 2023]
nav: true
nav_order: 1
---

<p><font size="5" color="#0000ff">presentations in international conference</font></p>

<p><font size="5" color="#0000ff">domestic conferences (non-reviewed)</font></p>
## domestic conferences (non-reviewed)

1. Abe, K. and Phung-Duc, T., “A diffusion limit of cognitive wireless networks with sensing time of secondary users,” Proceedings of the Queueing Symposium: Stochastic Models and their Applications, pp. 71--80, January 19-21, 2022, online.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
