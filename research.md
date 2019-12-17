---
layout: page
title: Research
permalink: /research/
custom_js:
- https://cdn.rawgit.com/pcooksey/bibtex-js/5ccf967/src/bibtex_js.js
---


<h2>Research Themes</h2>

<ul>
<li><em>Collective Adaptive Systems (CAS)</em>: programming models for programming CAS; aggregate computing.</li>
<li><em>Edge Computing</em>: programming models to coordinate resources across the edge-fog-cloud continuum.</li>
</ul>

<bibtex src="{{ '/assets/biblio.bib' | relative_url }}"></bibtex>

<h2>Publications</h2>

<div class="bibtex_structure">
  <div class="sections bibtextypekey">
    <div class="section @article">
      <h3>Journal Articles</h3>
      <div class="sort year" extra="DESC number">
        <div class="templates"></div>
      </div>
    </div>
    <div class="section @book">
      <h3>Books</h3>
      <div class="sort year" extra="DESC number">
        <div class="templates"></div>
      </div>
    </div>
    <div class="section @inproceedings">
      <h3>Conference and Workshop Papers</h3>
      <div class="sort year" extra="DESC number">
        <div class="templates"></div>
      </div>
    </div>
    <div class="section @misc|@phdthesis|@mastersthesis|@bachelorsthesis|@techreport">
      <h3>Other Publications</h3>
      <div class="sort year" extra="DESC number">
        <div class="templates"></div>
      </div>
    </div>
  </div>
</div>

<div class="bibtex_template">
  <div class="if author">
    <span class="if booktitle"><span class="booktitle"></span>.</span>
    <span class="if journal"><span class="journal"></span>.</span>
    <span class="if year">
      <span class="year"></span>.
    </span>
    <span class="author"><span class="first"></span> <span class="last"></span></span>
    <span class="if url">
      <a class="url">(view online)</a>
    </span>
  </div>
  <div>
    <span class="title"></span>
  </div>
</div>

<div id="bibtex_display"></div>
