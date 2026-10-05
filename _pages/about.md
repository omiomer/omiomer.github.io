---
layout: about
title: about
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

I am a Ph.D. candidate at Warwick Business School, University of Warwick, advised by [Juergen Branke](https://www.wbs.ac.uk/about/person/juergen-branke/) and Nursen Aydin. My research is on expensive decision-making problems, which appear throughout operations research, engineering and the sciences. Given a fixed budget for expensive evaluations, the goal is to choose the next experiment well while learning a black-box objective along the way. I work on Bayesian optimization and extend it to problem structures that are complex and difficult to solve.

Most of my recent work is on bilevel problems, in which a leader chooses an action and a follower responds to it, as in pricing when customers react to the price or in toll setting when drivers change their routes. My job market paper models both levels as Gaussian processes over the joint space of leader and follower decisions, so that what is learned about one follower problem carries over to similar ones. With my advisors, I am extending this framework to bilevel problems with multiple objectives at both levels.

I have also worked on surrogate models for Bayesian optimization. In a paper accepted at LION 20, I show that no single surrogate is best across problems and propose a mixture that uses a bandit rule to switch between Gaussian process and neural network surrogates. My current work combines Bayesian optimization with large language models, both to optimize prompts under an API budget and to decide which LLM-generated candidates are worth an expensive evaluation.

Alongside my Ph.D., I have been a research assistant at the UCL School of Management since 2023, where I built a decision-support tool for thalassemia treatment planning that is used by physicians. Before Warwick, I received an M.S. in Industrial Engineering and a B.S. in Electrical and Electronics Engineering from Bilkent University.

I am on the 2026–27 job market for faculty positions in operations research, operations management and business analytics, and for research roles in industry. My CV is available [here](/cv/).

## job market paper

<div class="publications">
{% bibliography --group_by none --query @*[keywords=jmp]* %}
</div>

## news

<!-- Keep the table inside div.news: al-folio's script otherwise marks the parent block as table-responsive, which pushes the bio below the photo. -->
<div class="news">
  <table class="table table-sm table-borderless">
    <tr><th scope="row" style="width: 20%">Jun 2026</th><td>Presented my job market paper at the SIAM Conference on Optimization (OP26), Edinburgh.</td></tr>
    <tr><th scope="row">Jun 2026</th><td>Presented <em>Combining Gaussian Processes and Neural Networks as Surrogate Models in Bayesian Optimization</em> at LION 20, Milan; LNCS proceedings forthcoming.</td></tr>
  </table>
</div>

## selected publications

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>

The full list of papers is on the [research](/publications/) page.

## references

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
