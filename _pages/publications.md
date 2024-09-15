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

---
### Book Chapters

- Abuso de Poder de Mercado en Situación de Dependencia Económica. (2016). 1st. Ed., Quito, Ecuador: SCPM. (with Vicente Abril; Eduardo Esparza; and Ricardo Freire).


---
### Pre-doctoral work (in Spanish)

- POBREZAECU: A Stata module to forecast poverty in Ecuador (2018). *Statistical Software Components.* Boston College Department of Economics. [[Report]()]

- El Efecto de la Gran Recesion sobre la Oferta Laboral en Ecuador (2017). *Atlantic Review of Economics*, Colexio de Economistas de Coruña, Spain and Fundación Una Galicia Moderna, vol. 1, pages 1-1, June.  (with [Nicolas Acosta](https://puceinvestiga.puce.edu.ec/en/persons/hugo-nicol%C3%A1s-acosta-gonz%C3%A1lez) and Ramiro Mejia) [[Paper](http://www.unagaliciamoderna.com/eawp/coldata/upload/Vol1_17_Oferta_Laboral_Ecuador.pdf)]

- Dependencia económica: el caso ecuatoriano (2016). *Economía y Política.* Facultad de Ciencias Económicas y Administrativas, Universidad de Cuenca., Vol. 24, pages 34-63. (with [Nicolas Acosta](https://puceinvestiga.puce.edu.ec/en/persons/hugo-nicol%C3%A1s-acosta-gonz%C3%A1lez) and Ramiro Mejia) [[Paper](https://dspace.ucuenca.edu.ec/bitstream/123456789/30213/1/1179-3607-1-PB.pdf)]
