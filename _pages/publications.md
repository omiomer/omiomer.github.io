---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 1
---

<!-- Sections are filled from _bibliography/papers.bib by each entry's `keywords` field. -->

<div class="publications">

<h2>Job Market Paper</h2>
{% bibliography --group_by none --query @*[keywords=jmp]* %}

<h2>Working Papers</h2>
{% bibliography --group_by none --query @*[keywords=working]* %}

<h2>Work in Progress</h2>
{% bibliography --group_by none --query @*[keywords=wip]* %}

<h2>Refereed Publications</h2>
{% bibliography --group_by none --query @*[keywords=refereed]* %}

</div>
