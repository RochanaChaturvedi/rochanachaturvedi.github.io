---
layout: page
permalink: /research/
title: Research
# years: [2024, 2020]
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->
<!-- <div class="publications">
    <h1> Publications </h1>
    <h6 align="right"><small>* indicates equal contribution</small></h6>
    {%- for y in page.years %}
    <h2 class="year">{{y}}</h2>
    {% bibliography -f papers -q @*[year={{y}}]* %}
    {% endfor %}
</div> -->

<div class="publications">
<h1> Publications </h1>
<h6 align="right"><small>* indicates equal contribution</small></h6>
{% bibliography %}
</div>

<div class="publications">
    <h1> Works in Progress </h1>
    {% bibliography -f progress %}
</div>
