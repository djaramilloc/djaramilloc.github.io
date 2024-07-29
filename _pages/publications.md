---
layout: page
permalink: /publications/
title: Research
description: 
years: [2024, 2023]
nav: true
nav_order: 2
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
### Work in Progress

- The criminogenic effects of releasing offenders. Evidence from Ecuador
- The Effect of Reduced Incarceration Length on Criminal Outcomes
- Religious Violence in Africa (with Siwan Anderson and Sara Benetti)
- Long-Term Effects of Missionary Activity on Conflict: Evidence from Ghana (with Siwan Anderson)

