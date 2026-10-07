---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: Research experience, publications, education, and computational research capabilities.
---

<style>
  .cv-intro {
    max-width: 820px;
    font-size: 1.02rem;
    line-height: 1.7;
    opacity: .82;
    margin-bottom: 1.8rem;
  }

  .cv-entry {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: .4rem 1.2rem;
    margin-bottom: .85rem;
  }

  .cv-entry .where {
    font-weight: 600;
  }

  .cv-entry .when {
    opacity: .66;
    white-space: nowrap;
    text-align: right;
  }

  .cv-entry .role {
    grid-column: 1 / -1;
    opacity: .88;
  }

  .cv-bullets {
    margin-top: .35rem;
    margin-bottom: 1.1rem;
  }

  .cv-bullets li {
    margin-bottom: .42rem;
    line-height: 1.6;
  }

  .cv-problem {
    border-top: 1px solid rgba(127,127,127,.18);
    padding: 1rem 0 1.05rem;
  }

  .cv-problem:last-child {
    border-bottom: 1px solid rgba(127,127,127,.18);
  }

  .cv-problem h4 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.03rem;
    font-weight: 600;
    margin-bottom: .4rem;
  }

  .cv-problem p {
    margin-bottom: .35rem;
    line-height: 1.62;
  }

  .cv-label {
    font-weight: 600;
  }

  .cv-methods {
    line-height: 1.7;
  }

  @media (max-width: 620px) {
    .cv-entry {
      grid-template-columns: 1fr;
    }

    .cv-entry .when {
      text-align: left;
    }
  }
</style>

<p class="cv-intro">
  Computational cancer immunology researcher integrating single-cell, immune-repertoire,
  clinical-genomic, proteomic, and cytometry data to study CAR-T persistence, clonal evolution,
  therapeutic response, and resistance.
</p>

## Education

<div class="cv-entry">
  <div class="where">University of Pennsylvania · Philadelphia, PA</div>
  <div class="when">Aug 2023 – May 2025</div>
  <div class="role">M.S.E. in Bioengineering</div>
</div>

<div class="cv-entry">
  <div class="where">Southwest University · Chongqing, China</div>
  <div class="when">Sept 2019 – Jun 2023</div>
  <div class="role">B.S. in Biotechnology</div>
</div>

## Research Experience

<div class="cv-entry">
  <div class="where">Center for Cellular Immunotherapies, University of Pennsylvania</div>
  <div class="when">June 2025 – Present</div>
  <div class="role"><strong>Bioinformatics Research Assistant · Ruella Lab</strong> · Philadelphia, PA</div>
</div>

<ul class="cv-bullets">
  <li>Led the computational analysis for a published <em>Nature Medicine</em> study on decade-long CD19 CAR-T persistence and immune-repertoire evolution, integrating longitudinal single-cell RNA-seq and TCR data to resolve persistent cell states, transcriptional programs, and clonotype dynamics.</li>
  <li>Analyzed targeted NGS and clinical data from CAR-T-treated lymphoma patients to test associations between genomic alterations and response, progression, toxicity, and survival.</li>
  <li>Analyzed longitudinal Olink proteomics data using paired/unpaired statistical modeling, multiple-testing correction, visualization, and biological interpretation across treatment time points.</li>
  <li>Analyzed high-dimensional flow-cytometry data with FlowSOM and UMAP, including cluster annotation, z-score heatmaps, cluster-abundance summaries, and CAR-positive versus CAR-negative subset comparisons.</li>
</ul>

<div class="cv-entry">
  <div class="where">Center for Cellular Immunotherapies, University of Pennsylvania</div>
  <div class="when">May 2024 – May 2025</div>
  <div class="role"><strong>Master's Research Assistant · Ruella Lab</strong> · Philadelphia, PA</div>
</div>

<ul class="cv-bullets">
  <li>Conducted integrated wet-lab and computational CAR-T research during M.S.E. training, supporting studies of CAR-T function, persistence, and immune-cell states.</li>
  <li>Performed T-cell expansion, in vitro killing assays, lentiviral production, T-cell transduction, flow cytometry-based CAR detection, Western blotting, ELISA, PCR, and ATAC-seq library preparation.</li>
</ul>

## Publications & Manuscripts

**Nature Medicine (2026)**  
*Decade-long persistence of CD19 CAR T cells in B cell lymphomas.*  
Fourth author; **led the computational analysis** and independently contributed to a significant proportion of the figures.  
[Paper ↗](https://doi.org/10.1038/s41591-026-04578-1) · [Analysis code ↗](https://github.com/EDCAKDC/GSE311890-CART-analysis)

**Journal for ImmunoTherapy of Cancer — submitted (2026)**  
*A CD20×CD55 bispecific antibody overcomes multi-axis CAR-T cell resistance to enhance CAR19+ T cell therapy in B-cell malignancies.*  
Co-author; contributed focused pre-treatment lymphoma gene-expression analysis and response-group visualization.

**Targeted NGS clinical genomics manuscript — in preparation**  
Contributed mutation profiling, clinical association analysis, survival analysis, Cox/logistic regression, gene-level comparison, and visualization in CAR-T-treated lymphoma patients.

**Olink proteomics manuscript — ongoing**  
Contributed longitudinal proteomics analysis, paired/unpaired statistical modeling, differential protein analysis, visualization, and biological interpretation.

## Selected Research Problems & Analytical Contributions

<div class="cv-problem">
  <h4>Long-term CAR-T persistence & clonal evolution</h4>
  <p><span class="cv-label">Question:</span> Which CAR-T cell states and clonotypes persist years after therapy, and how do they differ from peak expansion?</p>
  <p><span class="cv-label">Approach:</span> Integrated 10x scRNA-seq and VDJ/TCR data to compare longitudinal cell states, track persistent and dominant clonotypes, quantify repertoire diversity, and test transcriptional and pathway differences.</p>
</div>

<div class="cv-problem">
  <h4>Clinical genomics & treatment outcome</h4>
  <p><span class="cv-label">Question:</span> Which lymphoma-associated alterations are linked to response, progression, toxicity, or survival after CAR-T therapy?</p>
  <p><span class="cv-label">Approach:</span> Built clinical-genomic workflows spanning mutation-frequency profiling, pre/post-treatment comparison, Kaplan-Meier analysis, Cox/logistic modeling, odds ratios, and translational visualization.</p>
</div>

<div class="cv-problem">
  <h4>Multi-omics biomarker discovery</h4>
  <p><span class="cv-label">Question:</span> Do proteomic, transcriptomic, cytometry, and clinical signals converge on interpretable response-associated biology?</p>
  <p><span class="cv-label">Approach:</span> Analyzed longitudinal Olink data, integrated expression with clinical metadata, harmonized cross-source cytokine/protein datasets, and used group-wise statistics and PCA for biological interpretation.</p>
</div>

<div class="cv-problem">
  <h4>Systems-level T-cell metabolism</h4>
  <p><span class="cv-label">Question:</span> Which metabolic dependencies, nutrient constraints, and perturbations may reshape T-cell behavior in the tumor microenvironment?</p>
  <p><span class="cv-label">Approach:</span> Developed COBRApy workflows for FBA/FVA, gene/reaction knockout, synthetic lethality, E-Flux expression constraints, nutrient constraints, and flux-rewiring analysis.</p>
</div>

## Computational Research Capabilities

<p class="cv-methods">
<strong>Single-cell & immune repertoire:</strong> 10x scRNA-seq/VDJ integration, Seurat, Harmony, scRepertoire, pySCENIC/AUCell<br>
<strong>Clinical genomics & statistics:</strong> mutation/VAF analysis, Kaplan-Meier, Cox regression, logistic regression, multiple-testing correction<br>
<strong>Transcriptomics & functional analysis:</strong> DESeq2, edgeR, limma, STAR, featureCounts, Salmon, GSEA<br>
<strong>Flow cytometry:</strong> FlowSOM, UMAP, cluster-abundance analysis<br>
<strong>Epigenomics:</strong> ChIP-seq/ATAC-seq/CUT&RUN-oriented workflows, MACS2, deepTools, pyGenomeTracks, ChIPseeker<br>
<strong>Systems biology:</strong> COBRApy, FBA/FVA, knockout analysis, E-Flux<br>
<strong>Scientific computing:</strong> R, Python, Bash, Linux, Conda, Git/GitHub
</p>

## Research Interests

Computational cancer immunology · CAR-T biology · single-cell genomics · TCR repertoire analysis · translational bioinformatics · cancer genomics · multi-omics
