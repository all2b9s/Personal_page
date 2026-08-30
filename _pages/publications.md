---
layout: page
permalink: /publications/
title: Research
description: Research publications in cosmology, weak lensing, and astrophysics.
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

<h2>ML for shear estimation</h2>

{% bibliography --query @*[group=shear-estimation] %}

<h2>Baryonic feedback</h2>

{% bibliography --query @*[group=baryonic-feedback] %}

<h2>Asteroseismology</h2>

{% bibliography --query @*[group=asteroseismology] %}

<h2>Early works related to Dark Matter</h2>

{% bibliography --query @*[group=early-dark-matter] %}

</div>
