---
layout: page
permalink: /publications/
title: research
description:
nav: true
nav_order: 1
---

<!-- Sections are filled from _bibliography/papers.bib by each entry's `keywords` field. -->

<div class="publications">

<h2>job market paper</h2>
{% bibliography --group_by none --query @*[keywords=jmp]* %}

<h2>working papers</h2>
{% bibliography --group_by none --query @*[keywords=working]* %}

<h2>work in progress</h2>
{% bibliography --group_by none --query @*[keywords=wip]* %}

<h2>refereed publications</h2>
{% bibliography --group_by none --query @*[keywords=refereed]* %}

</div>
