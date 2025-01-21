---
layout: page
permalink: /publications/
title: publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
navigation_weight: 20
---

Only recent publications are listed here. The full list can be found in my [DBLP](https://dblp.org/pid/154/4313.html).

<div class="publications">

<h2 class="year">preprints</h2>
{% bibliography -f papers -q @*[preprint=true]* %}

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}} && preprint!=true]* %}
{% endfor %}

</div>