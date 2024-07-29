---
layout: page
permalink: /publications/
title: Research
description: 
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

- Long-Term Effects of Missionary Activity on Conflict: Evidence from Ghana (with Siwan Anderson)
- The Effect of Reduced Incarceration Length on Criminal Outcomes
