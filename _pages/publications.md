---
layout: page
permalink: /publications/
title: Publications
description: A list of my peer-reviewed publications. Please also have a look at "Projects" page for ongoing projects and other types of publications.
years: [2024, 2023, 2022, 2021, 2020, 2018, 2015]
nav: true
---
<!-- _pages/publication.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
