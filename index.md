---
layout: home
title:
permalink: /
eyebrow: Computer Scientist · Academic Leader
headline: Hridesh Rajan
role: Dean, School of Science &amp; Engineering
lede: Computer scientist and academic leader working across programming languages, software engineering, and trustworthy AI. At Tulane, I am building an interdisciplinary-first, translational School of Science and Engineering focused on Better Lives.
---

<section class="section">
  <div class="split">
    <div>
      <h2>Overview</h2>
      <p>I serve as the Dean of the <a href="https://sse.tulane.edu">School of Science and Engineering</a> at <a href="https://tulane.edu">Tulane University</a> and as a Professor in the <a href="https://sse.tulane.edu/cs">Department of Computer Science</a>. Before Tulane, I was the Kingland Professor and Chair of <a href="https://www.cs.iastate.edu">Computer Science</a> at <a href="https://www.iastate.edu">Iowa State University</a> (2019–2024) and the founding Professor-in-Charge of <a href="https://datascience.iastate.edu">Data Science Programs</a> (2017–2019).</p>
      <p>My research spans programming languages, software engineering, and trustworthy AI. I am known for the design of the <a href="https://link.springer.com/chapter/10.1007/978-3-540-70592-5_8">Ptolemy programming language</a>, which advanced modular reasoning about crosscutting concerns, and for <a href="https://github.com/boalang">Boa and its infrastructure</a>, which lowered the barriers to data-driven software engineering at ultra-large scale.</p>
      <p>I lead with a collaborative, outcomes-oriented style: building high-performing teams, launching programs that meet national needs, and creating partnerships that translate research into societal impact.</p>
      <p><a href="{{ site.baseurl }}/about/">Read the full biography &#8594;</a></p>
    </div>
    <aside class="contact-card">
      <h3>Contact</h3>
      <p class="addr">
        Office of the Dean<br>
        201 Lindy Claiborne Boggs Center<br>
        6823 St. Charles Avenue<br>
        New Orleans, LA 70118-5698, USA<br>
        Phone: (504) 865-5764
      </p>
      <p class="muted" style="margin-bottom:.6rem">Open to select advisory work, talks, and collaborations.</p>
      <p style="margin-bottom:.4rem"><a href="mailto:hrajan@tulane.edu">hrajan@tulane.edu</a></p>
      <p class="muted" style="margin-bottom:1rem">For scheduling and appointments, contact my assistant, LaShanda Robinson, at <a href="mailto:lrobins5@tulane.edu">lrobins5@tulane.edu</a>.</p>
      <p style="margin-bottom:0">
        <a href="https://www.linkedin.com/in/hrideshrajan/">LinkedIn</a> &middot;
        <a href="https://github.com/hridesh">GitHub</a> &middot;
        <a href="https://lab-design.github.io/">Lab</a>
      </p>
    </aside>
  </div>
</section>

<section class="section">
  <div class="section-head">
    <h2>Research</h2>
    <a class="more" href="{{ site.baseurl }}/research/">Explore research &#8594;</a>
  </div>
  <p class="lead">A single principle runs through my work: modular reasoning. I design the languages and interfaces that make it possible, scale it across millions of programs, and now carry it into AI-enabled systems.</p>
  <div class="cards">
    <a class="card" href="{{ site.baseurl }}/research/#modularity-and-modular-reasoning">
      <span class="card-tag">Thrust 01</span>
      <h3>Modularity &amp; Modular Reasoning</h3>
      <p>Languages, interfaces, and contracts for reasoning about complex software one module at a time.</p>
    </a>
    <a class="card" href="{{ site.baseurl }}/research/#software-at-scale">
      <span class="card-tag">Thrust 02</span>
      <h3>Software at Scale, with Boa</h3>
      <p>Expressing software-analysis tasks modularly so they run across the world's open-source code.</p>
    </a>
    <a class="card" href="{{ site.baseurl }}/research/#modular-and-dependable-ai">
      <span class="card-tag">Thrust 03</span>
      <h3>Modular &amp; Dependable AI</h3>
      <p>Decomposing learned models into modules and bringing software-engineering rigor to AI-enabled systems.</p>
    </a>
  </div>
</section>

<section class="section">
  <div class="section-head">
    <h2>Recent news</h2>
    <a class="more" href="{{ site.baseurl }}/news/">All news &#8594;</a>
  </div>
  <div class="cards">
    {% for post in site.posts limit:3 %}
    <a class="card" href="{{ site.baseurl }}{{ post.url }}">
      <span class="card-tag">{{ post.date | date: "%b %Y" }}</span>
      <h3>{{ post.title }}</h3>
    </a>
    {% endfor %}
  </div>
</section>

<section class="section">
  <div class="split">
    <div>
      <h2>Honors</h2>
      <ul class="pill-row">
        <li>AAAS Fellow</li>
        <li>US–UK Fulbright Scholar</li>
        <li>ACM Distinguished Member</li>
        <li>NSF CAREER Award</li>
      </ul>
      <p><a href="{{ site.baseurl }}/about/#major-awards-and-honors">See all awards and honors &#8594;</a></p>
    </div>
    <div>
      <h2>Selected service</h2>
      <ul class="tight-list">
        <li>Commissioner, <a href="https://www.abet.org/about-abet/governance/accreditation-commissions/">ABET Computing Accreditation Commission</a></li>
        <li>Co-chair, ASEE Engineering Deans Institute (EDI) 2027 Planning Committee</li>
        <li>General Chair, <a href="https://2021.splashcon.org/">SPLASH 2021</a> &amp; <a href="https://2020.splashcon.org/">2020</a></li>
        <li>Advisory Board, <a href="https://dl.acm.org/journal/pacmpl/editorial-board">PACMPL</a></li>
      </ul>
      <p><a href="{{ site.baseurl }}/service/">All service roles &#8594;</a></p>
    </div>
  </div>
</section>
