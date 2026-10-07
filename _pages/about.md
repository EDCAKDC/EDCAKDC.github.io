---
layout: about
title: about
permalink: /
subtitle: Computational Research Assistant · Penn Medicine

profile: false

selected_papers: true
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<div class="row">
  <div class="col-lg-9">
    <p class="text-uppercase small mb-2" style="letter-spacing:.14em; font-weight:600; opacity:.72;">
      Computational Cancer Immunology
    </p>
    <h2 style="font-size:clamp(2rem,5vw,3.4rem); line-height:1.08; margin-bottom:1rem;">
      From high-dimensional immune data<br>
      <span style="opacity:.68;">to translational insight.</span>
    </h2>
    <p class="lead" style="max-width:820px;">
      I work at the intersection of <strong>CAR-T cell therapy, single-cell genomics,
      immune-repertoire analysis, and translational bioinformatics</strong>.
    </p>
    <p style="max-width:860px;">
      My research uses molecular, cellular, and clinical data to study immune-cell states,
      clonal dynamics, and determinants of therapeutic response. I am particularly interested
      in computational approaches that connect mechanistic biology with clinically meaningful
      questions in cellular therapy and tumor immunology.
    </p>
  </div>
</div>

<div class="mt-5 mb-5">
  <div class="d-flex justify-content-between align-items-end flex-wrap mb-3">
    <div>
      <p class="text-uppercase small mb-1" style="letter-spacing:.12em; font-weight:600; opacity:.65;">Research pipeline</p>
      <h3 class="mb-0">How I approach a biological question</h3>
    </div>
    <p class="small mb-1 mt-2" style="opacity:.62;">multimodal data → reproducible computation → biological interpretation</p>
  </div>

  <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(185px,1fr)); gap:12px;">

    <div style="border:1px solid rgba(127,127,127,.25); border-radius:16px; padding:20px; min-height:220px;">
      <div class="small text-uppercase mb-3" style="letter-spacing:.12em; opacity:.55;">01 · Data</div>
      <h5 class="mb-3">Multimodal immune data</h5>
      <p class="small mb-3" style="opacity:.75;">Start from complementary views of tumor and immune biology.</p>
      <div class="d-flex flex-wrap gap-1">
        <span class="badge rounded-pill text-bg-light">scRNA-seq</span>
        <span class="badge rounded-pill text-bg-light">TCR / VDJ</span>
        <span class="badge rounded-pill text-bg-light">Flow cytometry</span>
        <span class="badge rounded-pill text-bg-light">Bulk RNA-seq</span>
        <span class="badge rounded-pill text-bg-light">Genomics</span>
        <span class="badge rounded-pill text-bg-light">Proteomics</span>
      </div>
    </div>

    <div style="border:1px solid rgba(127,127,127,.25); border-radius:16px; padding:20px; min-height:220px;">
      <div class="small text-uppercase mb-3" style="letter-spacing:.12em; opacity:.55;">02 · Process</div>
      <h5 class="mb-3">QC & integration</h5>
      <p class="small mb-3" style="opacity:.75;">Build analysis-ready datasets with reproducible preprocessing and harmonization.</p>
      <div class="d-flex flex-wrap gap-1">
        <span class="badge rounded-pill text-bg-light">Seurat</span>
        <span class="badge rounded-pill text-bg-light">Harmony</span>
        <span class="badge rounded-pill text-bg-light">STAR</span>
        <span class="badge rounded-pill text-bg-light">Salmon</span>
        <span class="badge rounded-pill text-bg-light">Git</span>
        <span class="badge rounded-pill text-bg-light">Conda</span>
      </div>
    </div>

    <div style="border:1px solid rgba(127,127,127,.25); border-radius:16px; padding:20px; min-height:220px;">
      <div class="small text-uppercase mb-3" style="letter-spacing:.12em; opacity:.55;">03 · Decode</div>
      <h5 class="mb-3">States & repertoires</h5>
      <p class="small mb-3" style="opacity:.75;">Resolve cellular phenotypes, clonal structure, longitudinal change, and immune programs.</p>
      <div class="d-flex flex-wrap gap-1">
        <span class="badge rounded-pill text-bg-light">scRepertoire</span>
        <span class="badge rounded-pill text-bg-light">FlowSOM</span>
        <span class="badge rounded-pill text-bg-light">UMAP</span>
        <span class="badge rounded-pill text-bg-light">SCENIC</span>
        <span class="badge rounded-pill text-bg-light">Clonotypes</span>
      </div>
    </div>

    <div style="border:1px solid rgba(127,127,127,.25); border-radius:16px; padding:20px; min-height:220px;">
      <div class="small text-uppercase mb-3" style="letter-spacing:.12em; opacity:.55;">04 · Model</div>
      <h5 class="mb-3">Statistics & pathways</h5>
      <p class="small mb-3" style="opacity:.75;">Quantify molecular differences and connect them to pathways, outcomes, and mechanisms.</p>
      <div class="d-flex flex-wrap gap-1">
        <span class="badge rounded-pill text-bg-light">DESeq2</span>
        <span class="badge rounded-pill text-bg-light">edgeR</span>
        <span class="badge rounded-pill text-bg-light">limma</span>
        <span class="badge rounded-pill text-bg-light">GSEA / fgsea</span>
        <span class="badge rounded-pill text-bg-light">Cox / KM</span>
        <span class="badge rounded-pill text-bg-light">COBRApy</span>
      </div>
    </div>

    <div style="border:1px solid rgba(127,127,127,.25); border-radius:16px; padding:20px; min-height:220px;">
      <div class="small text-uppercase mb-3" style="letter-spacing:.12em; opacity:.55;">05 · Translate</div>
      <h5 class="mb-3">Biological insight</h5>
      <p class="small mb-3" style="opacity:.75;">Turn computational signals into interpretable hypotheses relevant to cellular therapy.</p>
      <div class="d-flex flex-wrap gap-1">
        <span class="badge rounded-pill text-bg-light">Cell states</span>
        <span class="badge rounded-pill text-bg-light">Persistence</span>
        <span class="badge rounded-pill text-bg-light">Biomarkers</span>
        <span class="badge rounded-pill text-bg-light">Response</span>
        <span class="badge rounded-pill text-bg-light">Mechanism</span>
      </div>
    </div>

  </div>

  <div class="mt-3" style="border-radius:14px; padding:14px 18px; background:rgba(127,127,127,.07);">
    <div class="d-flex flex-wrap justify-content-between gap-2 small">
      <span><strong>Core languages:</strong> R · Python · Bash</span>
      <span><strong>Environment:</strong> Linux · Conda · Git</span>
      <span><strong>Output:</strong> reproducible pipelines · publication-ready analysis</span>
    </div>
  </div>
</div>

<hr>

### Featured work

<div class="row align-items-center">
  <div class="col-md-5">
    <a href="https://doi.org/10.1038/s41591-026-04578-1">
      <img src="{{ '/assets/img/nature-figure3.jpg' | relative_url }}" class="img-fluid rounded" alt="Representative analysis from the long-term CAR-T study">
    </a>
    <p class="caption mt-2"><strong>Representative analysis example.</strong> Figure 3 from the study.</p>
  </div>
  <div class="col-md-7">
    <p class="text-uppercase small mb-1" style="letter-spacing:.1em; opacity:.6;">Selected publication</p>
    <h4><em>Decade-long persistence of CD19 CAR T cells in B cell lymphomas</em></h4>
    <p><strong>Nature Medicine · 2026 · Co-author</strong></p>
    <p>
      I performed the <strong>computational analysis for the study</strong>, integrating
      single-cell transcriptomic and immune-repertoire data to characterize long-term
      persisting CAR-T cells.
    </p>
    <p>
      <strong>Analysis scope:</strong> single-cell state characterization, CAR<sup>+</sup>
      versus CAR<sup>−</sup> comparisons, peak-versus-year-9.3 longitudinal analysis,
      differential expression, pathway programs, TCR clonotype dynamics, and
      regulatory-state analysis.
    </p>
    <blockquote>“Z.Z. performed the computational analysis.” — Author Contributions</blockquote>
    <p>
      <a href="https://doi.org/10.1038/s41591-026-04578-1"><strong>Paper ↗</strong></a>
      &nbsp;·&nbsp;
      <a href="https://github.com/EDCAKDC/GSE311890-CART-analysis"><strong>Analysis code ↗</strong></a>
      &nbsp;·&nbsp;
      <a href="https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE311890"><strong>GEO ↗</strong></a>
    </p>
  </div>
</div>

<hr>

### Research domains

<div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(240px,1fr)); gap:16px;">
  <div style="border-left:3px solid currentColor; padding:6px 0 6px 18px;">
    <h5>CAR-T & tumor immunology</h5>
    <p class="mb-0">Long-term persistence, cell-state evolution, treatment response, memory, exhaustion, and translational cellular therapy.</p>
  </div>
  <div style="border-left:3px solid currentColor; padding:6px 0 6px 18px;">
    <h5>Single-cell & immune repertoire</h5>
    <p class="mb-0">scRNA-seq, longitudinal TCR clonotypes, repertoire diversity, cell-state annotation, regulon activity, and pathway analysis.</p>
  </div>
  <div style="border-left:3px solid currentColor; padding:6px 0 6px 18px;">
    <h5>Translational genomics</h5>
    <p class="mb-0">Cancer genomics, survival modeling, proteomics, flow cytometry, bulk transcriptomics, and multi-omics integration.</p>
  </div>
</div>

<p class="mt-4">
  <a href="{{ '/research/' | relative_url }}"><strong>Research overview →</strong></a>
  &nbsp;&nbsp;
  <a href="{{ '/projects/' | relative_url }}"><strong>Selected projects →</strong></a>
  &nbsp;&nbsp;
  <a href="{{ '/publications/' | relative_url }}"><strong>Publications →</strong></a>
</p>
