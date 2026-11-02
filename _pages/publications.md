---
layout: page
permalink: /academic/
title: Research
description: Academic publications and working papers
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Working Papers</h2>

{% bibliography --query @unpublished --group_by none %}

{% bibliography --query @article %}

</div>
