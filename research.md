---
layout: page-wide
title: Research
subtitle: Trustworthy AI and the software engineering of AI-enabled systems, grounded in programming languages and modular reasoning.
permalink: /research/
---

<section class="section">
  <div class="section-head"><h2>Interests</h2></div>
  <ul class="pill-row">
    <li>Trustworthy AI</li>
    <li>Software engineering of AI-enabled systems</li>
    <li>Programming languages</li>
    <li>Data-driven software engineering</li>
    <li>Modular reasoning</li>
  </ul>
</section>

<section class="section">
  <div class="section-head"><h2>Current research agenda</h2></div>
  <div class="prose">
    <p>I study the modularity of AI-enabled systems, with a particular focus on deep learning. Training, updating, and repurposing large models often consumes substantial financial and environmental resources. My approach is to <em>decompose deep neural networks into well-defined modules</em>, so that specific components can be isolated, reused, or replaced without retraining the entire model. The goal is sustainable, cost-aware AI development, where improvement and adaptation are local rather than global.</p>
    <p>My broader agenda is to enhance programmer productivity and improve the reliability of the systems we build. I design programming abstractions that reduce error-prone tasks, strengthen modular structure, and support <em>modular reasoning</em>. With these abstractions in place, compilers and frameworks can implement complex concerns automatically, lowering defect rates and accelerating development. By improving modularity and the structure of reasoning, we can scale analysis and verification for both human review and automated tooling.</p>
    <p>We are recruiting undergraduate students, graduate students, postdoctoral fellows, and in some cases research scientists for the projects below.</p>
  </div>
  <div class="cards">
    <a class="card" href="https://ieeexplore.ieee.org/document/6606588"><span class="card-tag">Infrastructure</span><h3>Boa infrastructure</h3><p>Expanding our cyberinfrastructure for big-data-driven discovery in software engineering: connecting Boa with LLMs, generating Boa-like infrastructure for new domains, and lowering query cost so it runs on smaller clusters.</p></a>
    <a class="card" href="https://dl.acm.org/doi/10.1109/ICSE55347.2025.00220"><span class="card-tag">Testing</span><h3>Separate testing of data &amp; AI models</h3><p>Building on Mock Deep Testing (ICSE 2025), our methodology for unit testing deep learning applications, and extending it to more kinds of models and data.</p></a>
    <a class="card" href="https://dl.acm.org/doi/10.1145/3597503.3623333"><span class="card-tag">Trustworthy AI</span><h3>Design by contract for AI systems</h3><p>Building on our ICSE 2024 work inferring data preconditions from deep learning models, and extending the approach to other models and properties.</p></a>
  </div>
  <div class="prose">
    <p>These three directions are active, and we are always happy to discuss follow-up work that builds on them. For the complete list of papers, visit my <a href="https://lab-design.github.io/papers/">lab's publications</a>.</p>
  </div>
</section>

<section class="section">
  <div class="section-head"><h2>Selected publications</h2><a class="more" href="{{ site.baseurl }}/publications/">All publications &#8594;</a></div>
  <div class="split">
    <div class="prose">
      <p>One of my long-term projects has been a new pedagogy, and a textbook, for teaching programming languages and functional programming to students who begin in an imperative language such as Java:</p>
      <p>Hridesh Rajan, <a href="https://mitpress.mit.edu/9780262045452/an-experiential-introduction-to-principles-of-programming-languages/"><em>An Experiential Introduction to Principles of Programming Languages</em></a>, MIT Press, Cambridge, MA, 304 pp., May 2022.</p>
      <p>See the <a href="{{ site.baseurl }}/publications/">Publications</a> page for representative work across programming languages, data-driven software engineering, and trustworthy AI.</p>
    </div>
    <div>
      <a href="https://mitpress.mit.edu/9780262045452/an-experiential-introduction-to-principles-of-programming-languages/"><img src="{{ site.baseurl }}/images/eipopl.jpeg" alt="Cover of An Experiential Introduction to Principles of Programming Languages" style="max-width:200px; border-radius:10px; box-shadow:0 8px 24px rgba(31,39,51,.14);"></a>
    </div>
  </div>
</section>

<section class="section">
  <p class="callout">Interested in collaborating, or in joining the lab as a student or postdoc? Reach me at <a href="mailto:hrajan@tulane.edu">hrajan@tulane.edu</a>, and see my <a href="{{ site.baseurl }}/prospective/">advice for prospective members</a>.</p>
</section>
