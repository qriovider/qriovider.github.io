---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2023]
nav: true
nav_order: 1
---

<p><font size="6" color="#8a2be2">presentations in international conference</font></p>

<p><font size="6" color="#8a2be2">domestic conferences (non-reviewed)</font></p>
1. Abe, K. and Phung-Duc, T., “A diffusion limit of cognitive wireless networks with sensing time of secondary users,” Proceedings of the Queueing Symposium: Stochastic Models and their Applications, pp. 71--80, January 19-21, 2022, online.


2. Abe, K. and Phung-Duc, “Asymptotic analysis of modefied Erlang B model considering interruptions,” Abstracts of The 2022 Fall National Conference of Operations Research Society of Japan, Niigata, Japan, 12-13 September 2022. (in Japanese).


<p><font size="6" color="#8a2be2">Refereed Papers in Proceedings of International Conferences</font></p>
1. Abe, K. and Phung-Duc, T., “Asymptotic analysis of modified Erlang-B system with sensing time and stochastic loss of secondary users,” to be presented and published in the Proceedings of Valuetools 2022.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
