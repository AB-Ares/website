---
layout: page
permalink: /publications/
title: Publications
description:
years: [2024, 2023, 2022, 2021, 2020, 2019]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
* **Orcid ID:** [0000-0002-5153-303X](https://orcid.org/0000-0002-5153-303X)
* **Google Scholar:** [aafNVpUAAAAJ&hl](https://scholar.google.com/citations?user=aafNVpUAAAAJ&hl)

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
