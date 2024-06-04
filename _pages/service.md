---
layout: page
permalink: /academic_service/
title: academic service
description: 
nav: true
nav_order: 4
---
<div class="publications">
  <header class="post-header">
    <h1 class="post-title">program committee member</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>
  {% bibliography -f committee %}
  </article>
  
  </div>
<div class="publications">
  <header class="post-header" style="margin-top:1.5cm;">
    <h1 class="post-title">external reviewer</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>
</div>

  <article>
  <div class="publications">
  {% bibliography -f reviews %}
</div>
  </article>

