---
layout: page
permalink: /publications/
title: publications
description: Here is a list of my publications, you can also find me in <a href=\"https://scholar.google.com/citations?user=TUR1VtcAAAAJ\"> Google Scholar</a>
years: [2024, 2023, 2022, 2021, 2020, 2018]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
