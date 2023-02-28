---
layout: publications
permalink: /publications/
title: publications
description: 
years: [2022, 2021]
#yearsp: [2022]
nav: true
---

<div class="publications">
  <header class="post-header">
    <h1 class="post-title">preprints</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>
  {% bibliography -f seminars %}
  </article>
  
  </div>
<div class="publications">
  <header class="post-header" style="margin-top:1.5cm;">
    <h1 class="post-title"> peer-reviewed publications</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>
</div>

  <article>
  <div class="publications">
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
</div>
  </article>
