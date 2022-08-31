---
layout: page
permalink: /publications/
title: Research
description: 
years: [2021]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<h3> Working Papers </h3>

<div class="publications">
  {%- for y in page.years %}
    <h2 class="year">{{y}}</h2>
    {% bibliography -f papers -q @*[year={{y}}]* %}
  {% endfor %}
</div>

---
<h3> Work in Progress </h3>

<ul>
  <li><em>Long-Term Effects of Missionary Activity on Conflict: Evidence from Ghana</em> with Siwan Anderson </li>
  <li><em>The Effect of Reduced Incarceration Length on Criminal Outcomes</em></li>
</ul>