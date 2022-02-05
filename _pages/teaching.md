---
layout: page
permalink: /activities/
title: teaching
description:
years: [2022, 2021, 2018]
nav: true
---

<article>

<div class="publications">
    {% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f courses -q @*[year={{y}}]* %}
{% endfor %}
</div>
</article>
