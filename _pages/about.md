---
layout: about
title: about
permalink: /
subtitle: Computational Research Assistant · Penn Medicine

profile: false

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  .zz-hero {
    padding: 1rem 0 2.3rem;
    max-width: 920px;
  }

  .zz-eyebrow {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .78rem;
    text-transform: uppercase;
    letter-spacing: .14em;
    font-weight: 700;
    opacity: .62;
    margin-bottom: .7rem;
  }

  .zz-identity {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    margin-bottom: 1.15rem;
    opacity: .78;
  }

  .zz-statement {
    font-family: "Roboto Slab", Georgia, serif;
    font-size: clamp(1.7rem, 3.3vw, 2.55rem);
    line-height: 1.26;
    font-weight: 400;
    letter-spacing: -.018em;
    max-width: 900px;
    margin: 0 0 1rem;
  }

  .zz-summary {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.02rem;
    line-height: 1.72;
    max-width: 820px;
    opacity: .84;
    margin-bottom: 1.15rem;
  }

  .zz-contact {
    display: flex;
    flex-wrap: wrap;
    gap: .55rem .9rem;
    font-family: "Roboto", Arial, sans-serif;
    font-size: .93rem;
    margin-top: 1.05rem;
  }

  .zz-contact a {
    text-decoration: none;
    font-weight: 500;
  }

  .zz-section-head {
    display: flex;
    justify-content: space-between;
    align-items: end;
    flex-wrap: wrap;
    gap: .75rem;
    margin-bottom: 1rem;
  }

  .zz-section-head h3 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: clamp(1.5rem, 2.5vw, 2rem);
    line-height: 1.25;
    font-weight: 500;
    letter-spacing: -.015em;
    margin: 0;
  }

  .zz-section-note {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .86rem;
    opacity: .6;
    margin: 0;
  }

  .zz-cap-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 16px;
  }

  .zz-cap-card {
    position: relative;
    overflow: hidden;
    border: 1px solid rgba(127,127,127,.18);
    border-radius: 18px;
    padding: 20px 20px 18px;
    background: rgba(127,127,127,.02);
  }

  .zz-cap-card::before {
    content: "";
    position: absolute;
    inset: 0 auto 0 0;
    width: 3px;
    background: var(--accent);
  }

  .zz-cap-kicker {
    font-family: "Roboto", Arial, sans-serif;
    color: var(--accent);
    font-size: .73rem;
    text-transform: uppercase;
    letter-spacing: .11em;
    font-weight: 700;
    margin-bottom: .65rem;
  }

  .zz-cap-card h4 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.16rem;
    line-height: 1.38;
    font-weight: 600;
    margin-bottom: .7rem;
  }

  .zz-cap-card p {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .94rem;
    line-height: 1.63;
    margin-bottom: .8rem;
    opacity: .84;
  }

  .zz-question {
    font-family: "Roboto", Arial, sans-serif;
    padding: .8rem .9rem;
    border-radius: 10px;
    background: color-mix(in srgb, var(--accent) 6%, transparent);
    font-size: .9rem;
    line-height: 1.52;
    margin-bottom: .7rem;
  }

  .zz-question strong {
    color: var(--accent);
    font-weight: 700;
  }

  .zz-evidence-line {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .82rem;
    line-height: 1.5;
    opacity: .68;
  }

  .zz-feature {
    border: 1px solid rgba(127,127,127,.18);
    border-radius: 18px;
    padding: 22px;
    background: rgba(127,127,127,.025);
  }

  .zz-feature-label {
    text-transform: uppercase;
    letter-spacing: .12em;
    font-size: .72rem;
    font-weight: 700;
    opacity: .54;
  }

  .zz-feature h4 {
    font-family: "Roboto Slab", Georgia, serif;
    font-size: 1.4rem;
    font-weight: 400;
    line-height: 1.38;
  }

  .zz-feature p,
  .zz-feature blockquote {
    font-family: "Roboto", Arial, sans-serif;
    line-height: 1.68;
  }

  .zz-feature blockquote {
    margin: .9rem 0;
    padding-left: 1rem;
    border-left: 3px solid rgba(127,127,127,.28);
    font-size: .94rem;
  }

  .zz-links a {
    margin-right: 1rem;
    white-space: nowrap;
  }

  .zz-caption {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .77rem;
    line-height: 1.5;
    opacity: .66;
  }

  .zz-nav {
    display: flex;
    flex-wrap: wrap;
    gap: .7rem 1.35rem;
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1rem;
  }

  @media (max-width: 760px) {
    .zz-cap-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<section class="zz-hero">
  <div class="zz-eyebrow">Computational cancer immunology</div>

  <div class="zz-identity">
    Ruella Lab · M.S.E. Bioengineering · University of Pennsylvania
  </div>

  <div class="zz-statement">
    I use immune data to understand why cellular therapies persist, respond, or fail.
  </div>

  <p class="zz-summary">
    My work focuses on CAR-T cell biology, single-cell genomics, immune repertoires, clinical genomics,
    and multi-omics. I integrate longitudinal molecular, cellular, and clinical evidence to study
    immune-cell states, clonal evolution, treatment response, and resistance.
  </p>

  <div class="zz-contact">
    <a href="mailto:zhengzh@pennmedicine.upenn.edu">Email ↗</a>
    <a href="https://github.com/EDCAKDC">GitHub ↗</a>
    <a href="https://orcid.org/0009-0002-6756-6052">ORCID ↗</a>
    <a href="{{ '/cv/' | relative_url }}">CV ↗</a>
  </div>
</section>

<hr>

<section class="my-5">
  <div class="zz-section-head">
    <div>
      <div class="zz-eyebrow mb-1">What I can do</div>
      <h3>Turn complex datasets into biological answers</h3>
    </div>
    <p class="zz-section-note">questions first · evidence attached</p>
  </div>

  <div class="zz-cap-grid">
    <div class="zz-cap-card" style="--accent:#0f766e;">
      <div class="zz-cap-kicker">Cell-state biology</div>
      <h4>Reconstruct how immune-cell states change across treatment and time</h4>
      <p>
        Resolve heterogeneous T-cell populations and compare functional programs across conditions
        and longitudinal time points.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Which cellular programs emerge, persist, disappear, or become enriched after therapy?
      </div>
      <div class="zz-evidence-line">
        <strong>Evidence:</strong> Nature Medicine 2026 · longitudinal 10x scRNA-seq · differential and pathway analysis
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#4f46e5;">
      <div class="zz-cap-kicker">Clonal dynamics</div>
      <h4>Track which T-cell clones expand, persist, and dominate over time</h4>
      <p>
        Link TCR clonotypes to cellular phenotypes, quantify repertoire diversity and dominance,
        and follow persistent clones across longitudinal samples.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Which clones survive years later, and what cellular states characterize those persistent clones?
      </div>
      <div class="zz-evidence-line">
        <strong>Evidence:</strong> 10x VDJ/TCR · clonotype tracking · repertoire entropy ·
        <a href="https://github.com/EDCAKDC/GSE311890-CART-analysis">analysis code ↗</a>
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#c76a12;">
      <div class="zz-cap-kicker">Response & outcome</div>
      <h4>Connect molecular and cellular features to therapeutic response</h4>
      <p>
        Test whether genomic alterations, proteins, or immune states are associated with response,
        relapse, toxicity, progression, or survival.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        What separates responders from non-responders, and which signals remain meaningful after clinical adjustment?
      </div>
      <div class="zz-evidence-line">
        <strong>Evidence:</strong> targeted NGS · Olink proteomics · Kaplan-Meier · Cox and logistic modeling
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#b4235a;">
      <div class="zz-cap-kicker">Multimodal integration</div>
      <h4>Integrate independent data types into a coherent mechanistic story</h4>
      <p>
        Bring together transcriptomics, immune repertoires, flow cytometry, genomics, proteomics,
        and clinical variables to test whether signals converge on the same biology.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Do different assays support the same mechanism, and which evidence is most clinically interpretable?
      </div>
      <div class="zz-evidence-line">
        <strong>Evidence:</strong> Olink · FlowSOM/UMAP · bulk expression · cross-dataset harmonization
      </div>
    </div>
  </div>
</section>

<section class="my-5">
  <div class="zz-section-head">
    <div>
      <div class="zz-eyebrow mb-1">Featured work</div>
      <h3>Decade-long CAR-T persistence</h3>
    </div>
  </div>

  <div class="zz-feature">
    <div class="row align-items-center g-4">
      <div class="col-md-5">
        <a href="{{ '/assets/img/nature-figure3-hires-white.png' | relative_url }}" target="_blank">
          <img
            src="{{ '/assets/img/nature-figure3-preview.png' | relative_url }}"
            class="img-fluid rounded"
            alt="Figure 3 from the long-term CAR-T persistence study"
          >
        </a>

        <p class="zz-caption mt-2 mb-0">
          Figure 3 from Paruzzo et al., <em>Nature Medicine</em> (2026), CC BY 4.0.
          Resized and converted to PNG for web display.
        </p>
      </div>

      <div class="col-md-7">
        <div class="zz-feature-label mb-2">Nature Medicine · 2026 · Fourth author</div>
        <h4><em>Decade-long persistence of CD19 CAR T cells in B cell lymphomas</em></h4>

        <p>
          I <strong>led the computational analysis</strong> for the study, integrating single-cell
          transcriptomic and immune-repertoire data to characterize long-term persisting CAR-T cells,
          state evolution, and clonotype dynamics.
        </p>

        <blockquote>“Z.Z. performed the computational analysis.” — Author Contributions</blockquote>

        <p class="zz-links mb-0">
          <a href="https://doi.org/10.1038/s41591-026-04578-1"><strong>Paper ↗</strong></a>
          <a href="https://github.com/EDCAKDC/GSE311890-CART-analysis"><strong>Analysis code ↗</strong></a>
          <a href="https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE311890"><strong>GEO ↗</strong></a>
        </p>
      </div>
    </div>
  </div>
</section>

<hr>

<section class="my-5">
  <div class="zz-nav">
    <a href="{{ '/research/' | relative_url }}"><strong>Research →</strong></a>
    <a href="{{ '/projects/' | relative_url }}"><strong>Projects →</strong></a>
    <a href="{{ '/publications/' | relative_url }}"><strong>Publications →</strong></a>
    <a href="{{ '/cv/' | relative_url }}"><strong>CV →</strong></a>
  </div>
</section>
