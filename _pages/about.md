---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate, <a href="https://www.wbs.ac.uk/">Warwick Business School</a>, University of Warwick. On the 2026–27 job market.

profile:
  align: right
  image: omer_ekmekcioglu.jpg
  image_circular: false
  more_info: >
    <p>Warwick Business School</p>
    <p>University of Warwick</p>
    <p>Coventry CV4 7AL, UK</p>

selected_papers: false # rendered inside the page body below, after the job market paper
social: true

announcements:
  enabled: false # news is a short table in the page body below

latest_posts:
  enabled: false
---

I am a Ph.D. candidate at Warwick Business School, University of Warwick, advised by [Juergen Branke](https://www.wbs.ac.uk/about/person/juergen-branke/) and Nursen Aydin. My research is on expensive decision-making problems. Given a fixed budget for expensive evaluations, the goal is to choose the next experiment well while learning a black-box objective along the way. I work on Bayesian optimization and extend it to problem structures that are complex and difficult to solve.

Most of my recent work is on bilevel problems. I have also worked on high-dimensional and multi-objective problems, and on surrogate models.

My current work brings principled Bayesian optimization methods to automated discovery with large language models.

Alongside my Ph.D., I have been a research assistant at the UCL School of Management since 2023, where I built a decision-support tool for thalassemia treatment planning that is used by physicians. Before Warwick, I received an M.S. in Industrial Engineering and a B.S. in Electrical and Electronics Engineering from Bilkent University.

I am on the 2026–27 job market for faculty positions in operations research, operations management and business analytics, and for research roles in industry. My CV is available [here](/cv/).

<!--
  Edit the text above freely. The HTML blocks below (div, table, row) are layout code:
  keep them as HTML and only change the words inside them. If an editor converts them
  to Markdown, the bio drops below the photo and the publication/reference styling breaks.
-->

## Job Market Paper

<div class="publications">
{% bibliography --group_by none --query @*[keywords=jmp]* %}
</div>

## News

<div class="news">
  <table class="table table-sm table-borderless">
    <tr><th scope="row" style="width: 20%">Jun 2026</th><td>Presented my job market paper at the SIAM Conference on Optimization (OP26), Edinburgh.</td></tr>
    <tr><th scope="row">Jun 2026</th><td>Presented <em>Combining Gaussian Processes and Neural Networks as Surrogate Models in Bayesian Optimization</em> at LION 20, Milan; LNCS proceedings forthcoming.</td></tr>
  </table>
</div>

## Selected Publications

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>

The full list of papers is on the [Research](/publications/) page.

## References

<div class="row references">
  <div class="col-sm-4" style="margin-bottom: 1rem">
    <strong>Juergen Branke</strong> (advisor)<br>
    Warwick Business School<br>
    University of Warwick<br>
    <a href="mailto:juergen.branke@wbs.ac.uk">juergen.branke@wbs.ac.uk</a>
  </div>
  <div class="col-sm-4" style="margin-bottom: 1rem">
    <strong>Nursen Aydin</strong> (advisor)<br>
    Warwick Business School<br>
    University of Warwick<br>
    <a href="mailto:nursen.aydin@wbs.ac.uk">nursen.aydin@wbs.ac.uk</a>
  </div>
  <div class="col-sm-4" style="margin-bottom: 1rem">
    <strong>Mustafa Ç. Pınar</strong><br>
    Industrial Engineering<br>
    Bilkent University<br>
    <a href="mailto:mustafap@bilkent.edu.tr">mustafap@bilkent.edu.tr</a>
  </div>
  <div class="col-sm-4" style="margin-bottom: 1rem">
    <strong>Ersin Korpeoglu</strong><br>
    UCL School of Management<br>
    University College London<br>
    <a href="mailto:e.korpeoglu@ucl.ac.uk">e.korpeoglu@ucl.ac.uk</a>
  </div>
  <div class="col-sm-4" style="margin-bottom: 1rem">
    <strong>Kenan Arifoglu</strong><br>
    UCL School of Management<br>
    University College London<br>
    <a href="mailto:k.arifoglu@ucl.ac.uk">k.arifoglu@ucl.ac.uk</a>
  </div>
</div>
