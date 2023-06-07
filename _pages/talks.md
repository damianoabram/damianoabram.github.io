---
layout: page
permalink: /talks/
title: talks
description: 
years: [2023, 2022, 2021]
yearsp: [2023, 2022, 2021]
nav: true
---
<div class="publications">
  <header class="post-header">
    <h1 class="post-title">seminars</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>

{% for y in page.yearsp %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f seminars -q @*[year={{y}}]* %}
{% endfor %}
  </article>
  
  </div>
<div class="publications">
  <header class="post-header" style="margin-top:1.5cm;">
    <h1 class="post-title">conference talks</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>
</div>

  <article>
  <div class="publications">
    {% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}
</div>
  </article>

