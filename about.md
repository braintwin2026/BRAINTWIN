---
layout: default
title: About
permalink: /about/
---

<!-- Page Header -->
<section class="page-header">
  <div class="container">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="{{ '/' | relative_url }}">Home</a></li>
        <li class="breadcrumb-item active" aria-current="page">About</li>
      </ol>
    </nav>
    <h1>About BRAINTWIN</h1>
  </div>
</section>

<!-- Main Content -->
<section class="section">
  <div class="container">
    <div class="row">
      <!-- Main column -->
      <div class="col-lg-8">
        <h2>Project Overview</h2>
        <p class="lead">
          BRAINTWIN (Brain Research through Advanced INTegration with Wide-scale Intelligent Networks) is a four-year research project developing digital twin technology for precision neurology.
        </p>

        <p>
          In neurology, where heterogeneity of disease obstructs conventional methods, digital twin technology offers a paradigm shift.
          For primary brain tumors (gliomas, meningiomas, and primary CNS lymphomas) and cerebral small vessel disease (SVD) — diseases with unpredictable courses and variable treatment outcomes —
          BRAINTWIN offers a novel architecture for patient-specific digital twin generation.
        </p>

        <h3 class="mt-5">Context and Justification</h3>
        <p>
          Current approaches based on population statistics and limited biomarkers fail to account for individual disease courses.
          There is no reliable tool to estimate recurrent stroke risk or cognitive decline in SVD patients.
          Personalized glioma and lymphoma treatment is made challenging by their molecular heterogeneity.
        </p>

        <p>
          BRAINTWIN brings together AI-driven modeling and multimodal data fusion (neuroimaging, histopathology, clinical data, and omics)
          to simulate disease development and treatment response, creating a “virtual patient” for each real patient.
        </p>

        <h3 class="mt-5">Research Objectives</h3>
        <ul class="list-group list-group-flush mb-4">
          <li class="list-group-item px-0">
            <i class="bi bi-check-circle-fill text-primary me-2"></i>
            Develop explainable multimodal fusion models using foundation models and cross-attention transformers
          </li>
          <li class="list-group-item px-0">
            <i class="bi bi-check-circle-fill text-primary me-2"></i>
            Implement resilient federated learning for GDPR-compliant training across hospital networks
          </li>
          <li class="list-group-item px-0">
            <i class="bi bi-check-circle-fill text-primary me-2"></i>
            Apply Schrodinger-bridge generative modeling for longitudinal disease trajectory prediction
          </li>
          <li class="list-group-item px-0">
            <i class="bi bi-check-circle-fill text-primary me-2"></i>
            Validate digital twins clinically in neuro-oncology and cerebrovascular disease
          </li>
          <li class="list-group-item px-0">
            <i class="bi bi-check-circle-fill text-primary me-2"></i>
            Release open-source software and benchmark datasets for the research community
          </li>
        </ul>

        <h3 class="mt-5">Expected Outcomes</h3>

        <div class="row g-4 mt-2">
          <div class="col-md-6">
            <div class="card h-100 border-0 shadow-sm">
              <div class="card-body">
                <h5><i class="bi bi-mortarboard text-primary me-2"></i>Scientific</h5>
                <ul class="small text-muted mb-0">
                  <li>New algorithms for multimodal fusion and federated learning</li>
                  <li>First validated brain digital twins</li>
                  <li>Reusable datasets and open-source pipelines</li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col-md-6">
            <div class="card h-100 border-0 shadow-sm">
              <div class="card-body">
                <h5><i class="bi bi-hospital text-primary me-2"></i>Clinical</h5>
                <ul class="small text-muted mb-0">
                  <li>Precision therapy recommendations for brain tumors</li>
                  <li>Personalized stroke/dementia risk prediction</li>
                  <li>Improved tumor board decision support</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Sidebar -->
      <div class="col-lg-4">
        <!-- 1) Project Details -->
        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body">
            <h5 class="card-title">Project Details</h5>
            <table class="table table-borderless small mb-0">
              <tr>
                <td class="text-muted">Duration:</td>
                <td><strong>2026 - 2029 (48 months)</strong></td>
              </tr>
              <tr>
                <td class="text-muted">Funding:</td>
                <td><strong>1.6 M EUR</strong></td>
              </tr>
              <tr>
                <td class="text-muted">Program:</td>
                <td><strong>ANR PEPR Sante Numerique</strong></td>
              </tr>
              <tr>
                <td class="text-muted">Framework:</td>
                <td><strong>France 2030</strong></td>
              </tr>
              <tr>
                <td class="text-muted">Coordinator:</td>
                <td><strong>Dr. Agusti Alentorn (ICM)</strong></td>
              </tr>
            </table>
          </div>
        </div>

        <!-- 2) Related Projects (moved directly below Project Details) -->
        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body">
            <h5 class="card-title">Related Projects</h5>
            <ul class="list-unstyled mb-0 small">
              <li class="mb-2">
                <a href="https://ai4scmed.github.io/" target="_blank" rel="noopener">
                  <i class="bi bi-link-45deg me-1"></i>AI4scMed
                </a>
              </li>
              <li class="mb-2">
                <a href="https://rhu-shiva.com/en/" target="_blank" rel="noopener">
                  <i class="bi bi-link-45deg me-1"></i>RHU SHIVA
                </a>
              </li>
              <li class="mb-2">
                <a href="https://vbhi-institute.org" target="_blank" rel="noopener">
                  <i class="bi bi-link-45deg me-1"></i>VBHI Bordeaux
                </a>
              </li>
              <li class="mb-2">
                <a href="https://pepr-santenum.fr" target="_blank" rel="noopener">
                  <i class="bi bi-link-45deg me-1"></i>PEPR Sante Numerique
                </a>
              </li>
            </ul>
          </div>
        </div>

        <!-- 3) Get in Touch (moved below Related Projects) -->
        <div class="card border-0 bg-primary text-white">
          <div class="card-body">
            <h5 class="card-title text-white">Get in Touch</h5>
            <p class="small mb-3">Interested in collaboration or have questions?</p>
            <a href="{{ '/contact/' | relative_url }}" class="btn btn-light btn-sm">Contact</a>
          </div>
        </div>
      </div>
      <!-- /Sidebar -->
    </div>
  </div>
</section>

<!-- Timeline -->
<section class="section section-light">
  <div class="container">
    <h2 class="section-title text-center mb-5">Project Timeline</h2>

    <div class="row justify-content-center">
      <div class="col-lg-8">
        <div class="timeline">
          <div class="timeline-item" data-aos="fade-up">
            <h5>Month 6 (M1)</h5>
            <p class="text-muted mb-0">Data platform operational with initial datasets (&gt;500 patients per domain)</p>
          </div>

          <div class="timeline-item" data-aos="fade-up" data-aos-delay="100">
            <h5>Month 12 (M2)</h5>
            <p class="text-muted mb-0">Initial multimodal model built and internally validated; integration of at least 3 modalities</p>
          </div>

          <div class="timeline-item" data-aos="fade-up" data-aos-delay="200">
            <h5>Month 18 (M3)</h5>
            <p class="text-muted mb-0">Federated learning successfully demonstrated between two sites</p>
          </div>

          <div class="timeline-item" data-aos="fade-up" data-aos-delay="300">
            <h5>Month 24 (M4)</h5>
            <p class="text-muted mb-0">Mid-term evaluation complete, refined model v2 and interim results</p>
          </div>

          <div class="timeline-item" data-aos="fade-up" data-aos-delay="400">
            <h5>Month 36 (M6)</h5>
            <p class="text-muted mb-0">Retrospective clinical validation for tumors done, manuscript drafted</p>
          </div>

          <div class="timeline-item" data-aos="fade-up" data-aos-delay="500">
            <h5>Month 48 (Final)</h5>
            <p class="text-muted mb-0">Project deliverables completed: final models, open-source release, dissemination events</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
