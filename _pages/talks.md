---
layout: page
permalink: /talks/
title: talks
description: 
nav: true
nav_order: 3
---
<div class="publications">
  <header class="post-header">
    <h1 class="post-title">seminars</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>
  {% bibliography -f seminars %}
  </article>
  
  </div>
<div class="publications">
  <header class="post-header" style="margin-top:1.5cm;">
    <h1 class="post-title">conference talks and workshops</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>
</div>

  <article>
  <div class="publications">
  {% bibliography -f conferences %}
</div>
  </article>

