---
layout: page
title: Research
permalink: /research/
custom_js:
- https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js
- /assets/js/bootstrap.bundle.min.js
- https://cdn.rawgit.com/pcooksey/bibtex-js/5ccf967/src/bibtex_js.js
description: Roberto Casadei's research themes and peer-reviewed publications.
---

# Research

## Research Themes

- _Self-* software systems_: architectures and models for self-adaptation and self-organisation.
- *Collective Intelligence*: programming models for programming collective adaptive systems; aggregate computing.
- *Edge Computing*: programming models to coordinate resources across the edge-fog-cloud continuum.

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
