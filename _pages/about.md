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

<style>
  .zz-hero {
    padding: 1.4rem 0 2.8rem;
    max-width: 900px;
  }

  .zz-eyebrow {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .78rem;
    text-transform: uppercase;
    letter-spacing: .14em;
    font-weight: 700;
    opacity: .66;
    margin-bottom: .8rem;
  }

  .zz-hero-title {
    font-family: "Roboto Slab", Georgia, serif;
    font-size: clamp(2.35rem, 5vw, 4.25rem);
    line-height: 1.04;
    font-weight: 400;
    letter-spacing: -.025em;
    margin: 0 0 1.25rem;
    max-width: 900px;
  }

  .zz-hero-title .muted {
    opacity: .56;
  }

  .zz-lead {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.2rem;
    line-height: 1.62;
    max-width: 820px;
    margin-bottom: .9rem;
  }

  .zz-sublead {
    font-family: "Roboto", Arial, sans-serif;
    max-width: 820px;
    font-size: 1rem;
    line-height: 1.72;
    opacity: .84;
  }

  .zz-section-head {
    display: flex;
    justify-content: space-between;
    align-items: end;
    flex-wrap: wrap;
    gap: .75rem;
    margin-bottom: 1.15rem;
  }

  .zz-section-head h3 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: clamp(1.55rem, 2.6vw, 2.05rem);
    line-height: 1.25;
    font-weight: 500;
    letter-spacing: -.015em;
    margin: 0;
  }

  .zz-section-note {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .88rem;
    line-height: 1.45;
    opacity: .62;
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
    border-radius: 20px;
    padding: 24px 24px 22px;
    min-height: 250px;
    background: rgba(127,127,127,.025);
  }

  .zz-cap-card::before {
    content: "";
    position: absolute;
    inset: 0 auto 0 0;
    width: 4px;
    background: var(--accent);
  }

  .zz-cap-card::after {
    content: "";
    position: absolute;
    width: 180px;
    height: 180px;
    right: -80px;
    top: -90px;
    border-radius: 50%;
    background: var(--glow);
    pointer-events: none;
  }

  .zz-cap-kicker {
    font-family: "Roboto", Arial, sans-serif;
    color: var(--accent);
    font-size: .76rem;
    text-transform: uppercase;
    letter-spacing: .12em;
    font-weight: 700;
    margin-bottom: .9rem;
  }

  .zz-cap-card h4 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.3rem;
    line-height: 1.34;
    font-weight: 500;
    letter-spacing: -.01em;
    margin-bottom: .9rem;
    max-width: 94%;
  }

  .zz-cap-card p {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .98rem;
    line-height: 1.72;
    margin-bottom: 1rem;
    opacity: .86;
  }

  .zz-question {
    font-family: "Roboto", Arial, sans-serif;
    margin-top: 1.05rem;
    padding: .9rem 1rem;
    border: 0;
    border-radius: 12px;
    background: color-mix(in srgb, var(--accent) 7%, transparent);
    font-size: .94rem;
    line-height: 1.58;
  }

  .zz-question strong {
    color: var(--accent);
    font-weight: 700;
  }

  .zz-flow {
    margin-top: 1.4rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    border: 1px solid rgba(127,127,127,.16);
    border-radius: 18px;
    overflow: hidden;
  }

  .zz-flow-item {
    padding: 18px 18px 16px;
    min-height: 125px;
    position: relative;
  }

  .zz-flow-item + .zz-flow-item {
    border-left: 1px solid rgba(127,127,127,.14);
  }

  .zz-flow-step {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .72rem;
    text-transform: uppercase;
    letter-spacing: .11em;
    opacity: .58;
    margin-bottom: .5rem;
  }

  .zz-flow-item strong {
    font-family: "Roboto", Arial, sans-serif;
    display: block;
    font-size: 1rem;
    line-height: 1.42;
    font-weight: 600;
    margin-bottom: .4rem;
  }

  .zz-flow-item span {
    font-family: "Roboto", Arial, sans-serif;
    display: block;
    font-size: .88rem;
    line-height: 1.58;
    opacity: .76;
  }

  .zz-feature {
    border: 1px solid rgba(127,127,127,.16);
    border-radius: 22px;
    padding: 22px;
    background: linear-gradient(135deg, rgba(15,118,110,.055), rgba(79,70,229,.025) 55%, rgba(190,18,60,.025));
  }

  .zz-feature-label {
    text-transform: uppercase;
    letter-spacing: .13em;
    font-size: .72rem;
    font-weight: 700;
    opacity: .52;
  }

  .zz-feature h4 {
    font-family: "Roboto Slab", Georgia, serif;
    font-size: 1.42rem;
    font-weight: 400;
    line-height: 1.38;
  }

  .zz-feature p,
  .zz-feature blockquote {
    font-family: "Roboto", Arial, sans-serif;
    line-height: 1.68;
  }

  .zz-evidence {
    border-left: 3px solid #0f766e;
    padding-left: 15px;
    margin: 1rem 0 1.1rem;
  }

  .zz-links a {
    margin-right: 1rem;
    white-space: nowrap;
  }

  .zz-question-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
  }

  .zz-question-card {
    padding: 18px 4px 14px 18px;
    border-left: 3px solid var(--accent);
  }

  .zz-question-card h5 {
    font-family: "Roboto", Arial, sans-serif;
    font-size: 1.08rem;
    font-weight: 600;
    margin-bottom: .55rem;
  }

  .zz-question-card p {
    font-family: "Roboto", Arial, sans-serif;
    font-size: .96rem;
    margin: 0;
    line-height: 1.68;
    opacity: .82;
  }

  @media (max-width: 820px) {
    .zz-cap-grid,
    .zz-question-grid {
      grid-template-columns: 1fr;
    }

    .zz-flow {
      grid-template-columns: 1fr 1fr;
    }

    .zz-flow-item + .zz-flow-item {
      border-left: 0;
    }

    .zz-flow-item:nth-child(even) {
      border-left: 1px solid rgba(127,127,127,.14);
    }

    .zz-flow-item:nth-child(n+3) {
      border-top: 1px solid rgba(127,127,127,.14);
    }
  }

  @media (max-width: 520px) {
    .zz-flow {
      grid-template-columns: 1fr;
    }

    .zz-flow-item:nth-child(even) {
      border-left: 0;
    }

    .zz-flow-item + .zz-flow-item {
      border-top: 1px solid rgba(127,127,127,.14);
    }
  }
</style>

<section class="zz-hero">
  <div class="zz-eyebrow">Research focus</div>
  <h1 class="zz-hero-title">
    I use immune data to explain<br>
    <span class="muted">why cellular therapies persist, respond, or fail.</span>
  </h1>

  <p class="zz-lead">
    My work centers on <strong>CAR-T cell biology, single-cell genomics, immune repertoires,
    and translational cancer research</strong>.
  </p>

  <p class="zz-sublead">
    I combine longitudinal molecular, cellular, and clinical evidence to reconstruct immune-cell
    states, track clonal evolution, and identify mechanisms associated with therapeutic response.
  </p>
</section>

<section class="mb-5">
  <div class="zz-section-head">
    <div>
      <div class="zz-eyebrow mb-1">What I can do</div>
      <h3>Turn complex datasets into biological answers</h3>
    </div>
    <p class="zz-section-note">longitudinal · multimodal · clinically grounded</p>
  </div>

  <div class="zz-cap-grid">

    <div class="zz-cap-card" style="--accent:#0f766e; --glow:rgba(15,118,110,.08);">
      <div class="zz-cap-kicker">Cell-state biology</div>
      <h4>Reconstruct how immune-cell states change across treatment and time</h4>
      <p>
        Resolve heterogeneous T-cell populations, identify memory, activation, exhaustion,
        proliferation, and other functional programs, and compare those states across conditions
        or longitudinal time points.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Which cellular programs emerge, persist, disappear, or become enriched after therapy?
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#4f46e5; --glow:rgba(79,70,229,.08);">
      <div class="zz-cap-kicker">Clonal dynamics</div>
      <h4>Track which T-cell clones expand, persist, and dominate over time</h4>
      <p>
        Link TCR clonotypes to cellular phenotypes, quantify repertoire diversity and dominance,
        and follow shared or persistent clones across longitudinal samples.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Which clones survive years later, and what cellular states characterize those persistent clones?
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#c76a12; --glow:rgba(199,106,18,.08);">
      <div class="zz-cap-kicker">Response & outcome</div>
      <h4>Connect molecular and cellular features to therapeutic response</h4>
      <p>
        Test whether genomic alterations, proteins, immune states, or other biomarkers are associated
        with response, relapse, toxicity, progression, or survival.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        What separates responders from non-responders, and which signals remain meaningful after clinical adjustment?
      </div>
    </div>

    <div class="zz-cap-card" style="--accent:#b4235a; --glow:rgba(180,35,90,.075);">
      <div class="zz-cap-kicker">Multimodal integration</div>
      <h4>Integrate independent data types into a coherent mechanistic story</h4>
      <p>
        Bring together single-cell transcriptomics, immune repertoires, flow cytometry,
        bulk RNA-seq, cancer genomics, proteomics, and clinical variables to test whether
        independent signals converge on the same biology.
      </p>
      <div class="zz-question">
        <strong>Questions I can answer:</strong><br>
        Do different assays support the same mechanism, and which evidence is most clinically interpretable?
      </div>
    </div>

  </div>

  <div class="zz-flow">
    <div class="zz-flow-item">
      <div class="zz-flow-step">01 · Define</div>
      <strong>Start with the biological question</strong>
      <span>Persistence, clonal evolution, response, resistance, or mechanism.</span>
    </div>
    <div class="zz-flow-item">
      <div class="zz-flow-step">02 · Resolve</div>
      <strong>Extract interpretable structure</strong>
      <span>Cell states, clones, molecular programs, clinical subgroups, longitudinal change.</span>
    </div>
    <div class="zz-flow-item">
      <div class="zz-flow-step">03 · Test</div>
      <strong>Quantify the evidence</strong>
      <span>Differential signals, associations, pathways, survival, and cross-modal agreement.</span>
    </div>
    <div class="zz-flow-item">
      <div class="zz-flow-step">04 · Translate</div>
      <strong>Return to the biology</strong>
      <span>Mechanistic interpretation, response hypotheses, and publication-ready evidence.</span>
    </div>
  </div>
</section>

<hr>

<section class="my-5">
  <div class="zz-section-head">
    <div>
      <div class="zz-eyebrow mb-1">Featured work</div>
      <h3>Long-term CAR-T persistence</h3>
    </div>
  </div>

  <div class="zz-feature">
    <div class="row align-items-center g-4">
      <div class="col-md-5">
        <a href="https://doi.org/10.1038/s41591-026-04578-1">
          <img
            src="{{ '/assets/img/nature-figure3.jpg' | relative_url }}"
            class="img-fluid rounded"
            alt="Representative analysis from the long-term CAR-T study"
          >
        </a>
        <p class="caption mt-2 mb-0">
          Representative analysis example · Figure 3 from the study
        </p>
      </div>

      <div class="col-md-7">
        <div class="zz-feature-label mb-2">Nature Medicine · 2026 · Co-author</div>
        <h4><em>Decade-long persistence of CD19 CAR T cells in B cell lymphomas</em></h4>

        <p>
          I performed the <strong>computational analysis for the study</strong>, integrating
          single-cell transcriptomic and immune-repertoire data to characterize long-term
          persisting CAR-T cells.
        </p>

        <div class="zz-evidence">
          <strong>What the analysis addressed</strong>
          <div class="small mt-1" style="opacity:.74;">
            How CAR-T cell states changed from peak expansion to year 9.3, which transcriptional
            programs distinguished persistent cells, and how clonotype structure evolved over time.
          </div>
        </div>

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
  <div class="zz-section-head">
    <div>
      <div class="zz-eyebrow mb-1">Research questions</div>
      <h3>The problems I want to keep working on</h3>
    </div>
  </div>

  <div class="zz-question-grid">
    <div class="zz-question-card" style="--accent:#0f766e;">
      <h5>Persistence</h5>
      <p>What allows engineered T cells to persist, adapt, and remain functional over years?</p>
    </div>

    <div class="zz-question-card" style="--accent:#4f46e5;">
      <h5>Clonal evolution</h5>
      <p>How do immune repertoires and dominant clonotypes change across treatment and time?</p>
    </div>

    <div class="zz-question-card" style="--accent:#b4235a;">
      <h5>Response & resistance</h5>
      <p>Which molecular and cellular features explain therapeutic response, failure, or relapse?</p>
    </div>
  </div>

  <p class="mt-4">
    <a href="{{ '/research/' | relative_url }}"><strong>Research overview →</strong></a>
    &nbsp;&nbsp;
    <a href="{{ '/projects/' | relative_url }}"><strong>Selected projects →</strong></a>
    &nbsp;&nbsp;
    <a href="{{ '/publications/' | relative_url }}"><strong>Publications →</strong></a>
  </p>
</section>
