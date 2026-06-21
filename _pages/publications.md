---
layout: page
permalink: /publications/
title: Research
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<!-- Sections are rendered in an explicit order below (not alphabetical) so that
     "Work in Progress" stays at the bottom. group_by: abbr (in _config.yml) still
     renders each section's styled header automatically. -->

<div class="publications">

{% bibliography --query @*[abbr=Publications]* %}

{% bibliography --query @*[abbr=Working Papers]* %}

{% bibliography --query @*[abbr=Work in Progress]* %}

</div>
