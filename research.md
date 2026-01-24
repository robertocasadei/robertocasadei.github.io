---
layout: default
title: Research
permalink: /research/
custom_js:
- /assets/js/jquery.min.js
- /assets/js/bootstrap.bundle.min.js
- /assets/js/bibtex_js.js
description: Roberto Casadei's research themes and peer-reviewed publications.
---

# Research

**Main research theme.** Since my Masters' Degree Thesis in 2016 and through my PhD (2016-2020), post-doc (2020-2022), and assistant professor roles (2022-2026), my research has focussed on the **software engineering of collective systems**, especially by the computational, programming language,  and distributed middleware perspectives. 

**Contributions.** Contributions include developments of the **aggregate computing paradigm** (cf. concrete languages like ScaFi, and middleware models for the edge-cloud continuum like *pulverisation*), conceptualisation of **macro-programming**, investigations about **artificial collective intelligence**, identification and definition of **self-organisation design patterns**, and conceptualisation of application scenarios like **crowd digital twins**. 

## Research Themes at a Glance

- **Self-* software systems**: architectures and models for self-adaptation and self-organisation.
- **(Unconventional) Programming Languages**: programming language-based approaches for emergent, collective intelligent, and self-organising systems (cf. Macro-programming).
- **(Artificial &amp; Hybrid) Collective Intelligence**: theories, models, and techniques for understanding and engineering CI in (hybrid) multi-agent systems.
- **IoT, Smart Cities &amp; Edge Computing**: programming models to express computations and coordinate resources across the IoT-edge-fog-cloud continuum and in large-scale scenarios (e.g., smart cities).

<bibtex src="{{ '/assets/biblio.bib' | relative_url }}"></bibtex>

## Publications

Click on the symbol <i class="fas fa-info-circle"></i> for a paper commentary.

<div class="bibtex_structure">
  <div class="group year" extra="DESC number">
    <h3 class="title"></h3>
    <div class="templates"></div>
  </div>                                                            
</div>

<div class="bibtex_template">
  <div>
    <span class="title"></span>
  </div>
  <div class="if author"><span class="author"><span class="first"></span> <span class="last"></span></span></div>
  <span class="if booktitle"><span class="booktitle"></span>.</span>
  <span class="if journal"><span class="journal"></span>.</span>
  <span class="if year">
  <span class="year"></span>.
  <span class="if note">
    <!--<button class="bibtexVar" type="button" data-toggle="collapse" data-target="#notes_+BIBTEXKEY+" extra="BIBTEXKEY" role="button" aria-expanded="false" aria-controls="notes_+BIBTEXKEY+"><i class="fas fa-envelope"></i></button>-->
    <a class="bibtexVar" type="button" data-toggle="collapse" href="#notes_+BIBTEXKEY+" extra="BIBTEXKEY" role="button" aria-expanded="false" aria-controls="notes_+BIBTEXKEY+"><i class="fas fa-info-circle"></i></a>
  </span>
  </span>
  <div class="if url">
    <a class="bibtexVar" href="+URL+" extra="url">
      <span class="url"></span>
    </a>
  </div>
  <div class="if !url">
    <div class="if doi">
      <a class="bibtexVar" href="" extra="doi"><span class="doi"></span></a>
    </div>
  </div>
  <div class="note collapse bibtexVar" id="notes_+BIBTEXKEY+" extra="BIBTEXKEY">
    <span extra="note" class="note"></span>
  </div>
</div>

<div id="bibtex_display"></div>
