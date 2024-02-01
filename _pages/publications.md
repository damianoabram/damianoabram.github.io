---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---
<div class="publications">
  <header class="post-header">
    <h1 class="post-title">preprints</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>
  {% bibliography -f papers %}
  </article>
  
  </div>
<div class="publications">
  <header class="post-header" style="margin-top:1.5cm;">
    <h1 class="post-title">peer-reviewed publications</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>
</div>

  <article>
  <div class="publications">
  {% bibliography -f papers %}
</div>
  </article>
