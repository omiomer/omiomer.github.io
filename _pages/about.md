---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate · <a href="https://www.wbs.ac.uk/">Warwick Business School</a>, University of Warwick · <strong>On the 2026–27 academic and industry job market</strong>

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

I am a Ph.D. candidate in the ISMA group at Warwick Business School, advised by [Juergen Branke](https://www.wbs.ac.uk/about/person/juergen-branke/) and Nursen Aydin. My research asks a practical question: **given a fixed budget of expensive experiments, which one should be run next?** I develop Bayesian optimization methods for problems where every evaluation is costly — bilevel problems in which a leader must anticipate how a follower will respond, multi-objective problems, and high-dimensional black boxes — with applications in pricing under strategic response, toll setting and mechanism design.

Alongside my Ph.D., I have been a research assistant at the UCL School of Management since 2023. Before Warwick, I completed an M.S. in Industrial Engineering and a B.S. in Electrical and Electronics Engineering at Bilkent University.

I am on the 2026–27 job market for **faculty positions** in operations research, operations management and business analytics, and for **industry research roles** in Bayesian optimization, experimentation and applied machine learning. My [CV is here](/cv/).

**Research interests:** Bayesian optimization · bilevel and multi-objective optimization · simulation optimization · machine learning for operations

## job market paper

<div class="publications">
{% bibliography --group_by none --query @*[keywords=jmp]* %}
</div>

Bilevel problems in which both the leader's and the follower's objectives are expensive black boxes. Both levels are modelled as Gaussian processes, and an acquisition strategy allocates a fixed evaluation budget across the two levels, so the follower's response is estimated rather than computed.

## news

<!-- Keep the table inside div.news: al-folio's script otherwise marks the parent block as table-responsive, which pushes the bio below the photo. -->
<div class="news">
  <table class="table table-sm table-borderless">
    <tr><th scope="row" style="width: 20%">Oct 2026</th><td>On the 2026–27 academic and industry job market.</td></tr>
    <tr><th scope="row">Jun 2026</th><td>Presented my job market paper at the SIAM Conference on Optimization (OP26), Edinburgh.</td></tr>
    <tr><th scope="row">Jun 2026</th><td>Presented <em>Combining Gaussian Processes and Neural Networks as Surrogate Models in Bayesian Optimization</em> at LION 20, Milan; LNCS proceedings forthcoming.</td></tr>
  </table>
</div>

## selected publications

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>

See all [research](/publications/).

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
