---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order. <sup>*</sup> denotes equal contribution.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<style>
  /* Make my own name (theme emphasizes it with <em>) stand out in bold. */
  .publications .author em {
    font-weight: 700;
    font-style: normal;
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
