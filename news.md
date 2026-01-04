---
layout: default
title: News
permalink: /news/
---

<!-- Page Header -->
<section class="page-header">
  <div class="container">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="{{ '/' | relative_url }}">Home</a></li>
        <li class="breadcrumb-item active" aria-current="page">News</li>
      </ol>
    </nav>
    <h1>News & Events</h1>
  </div>
</section>

<!-- News + Sidebar (same row, stable layout like About) -->
<section class="section">
  <div class="container">
    <div class="row g-4 align-items-start">
      <!-- Main column -->
      <div class="col-lg-8">
        <p class="lead mb-4">
          Project updates, funding milestones, and upcoming events from the BRAINTWIN consortium.
        </p>

        <!-- News Item -->
        <article class="card mb-4 border-0 shadow-sm" data-aos="fade-up">
          <div class="card-body p-4">
            <div class="d-flex flex-wrap align-items-center gap-2 mb-3">
              <span class="badge bg-primary">Project News</span>
              <span class="text-muted small">January 2026</span>
            </div>
            <h3 class="h4 mb-3">BRAINTWIN Project Officially Launches</h3>
            <p>
              We are excited to announce the official launch of the BRAINTWIN project! The kickoff meeting brought together all
              consortium partners at the Paris Brain Institute (ICM) to discuss the project roadmap, work package responsibilities,
              and collaboration strategies.
            </p>
            <p class="mb-0">
              The four-year project, funded by ANR under the PEPR Sante Numerique program of France 2030, aims to develop digital twin
              technology for precision neurology, focusing on brain tumors and cerebral small vessel disease.
            </p>
          </div>
        </article>

        <article class="card mb-4 border-0 shadow-sm" data-aos="fade-up" data-aos-delay="100">
          <div class="card-body p-4">
            <div class="d-flex flex-wrap align-items-center gap-2 mb-3">
              <span class="badge bg-success">Funding</span>
              <span class="text-muted small">December 2025</span>
            </div>
            <h3 class="h4 mb-3">ANR Funding Approved for BRAINTWIN</h3>
            <p class="mb-0">
              The BRAINTWIN project has received funding approval from the French National Research Agency (ANR) as part of the PEPR
              Sante Numerique initiative under France 2030. The consortium will receive 1.6 million euros over 48 months to develop
              innovative digital twin solutions for neurological diseases.
            </p>
          </div>
        </article>

        <article class="card mb-4 border-0 shadow-sm" data-aos="fade-up" data-aos-delay="200">
          <div class="card-body p-4">
            <div class="d-flex flex-wrap align-items-center gap-2 mb-3">
              <span class="badge bg-info text-dark">Opportunity</span>
              <span class="text-muted small">Coming Soon</span>
            </div>
            <h3 class="h4 mb-3">PhD and Postdoc Positions Available</h3>
            <p>Multiple PhD and postdoctoral positions will be available across consortium partner institutions. Research areas include:</p>
            <ul class="mb-3">
              <li>Multimodal deep learning for medical imaging</li>
              <li>Federated learning and privacy-preserving AI</li>
              <li>Computational pathology and whole-slide image analysis</li>
              <li>Clinical validation of AI models in neuro-oncology and stroke</li>
            </ul>
            <p class="mb-0">
              Check back soon for application details or <a href="{{ '/contact/' | relative_url }}">contact us</a> for more information.
            </p>
          </div>
        </article>
      </div>

      <!-- Sidebar column -->
      <div class="col-lg-4">
        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body">
            <h5 class="card-title">Upcoming Events</h5>
            <ul class="list-unstyled mb-0">
              <li class="mb-3 pb-3 border-bottom">
                <span class="small text-muted d-block">Q1 2026</span>
                <strong>First Consortium Meeting</strong>
                <p class="small text-muted mb-0">Paris, France</p>
              </li>
              <li class="mb-3 pb-3 border-bottom">
                <span class="small text-muted d-block">2026</span>
                <strong>MICCAI 2026</strong>
                <p class="small text-muted mb-0">Conference presentations</p>
              </li>
              <li>
                <span class="small text-muted d-block">2027</span>
                <strong>Workshop on Digital Twins in Neurology</strong>
                <p class="small text-muted mb-0">ICM Paris (planned)</p>
              </li>
            </ul>
          </div>
        </div>

        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body">
            <h5 class="card-title">Stay Updated</h5>
            <p class="small text-muted mb-3">Follow us on social media for the latest updates:</p>

            <div class="d-flex align-items-center gap-3 flex-wrap">
              <a href="https://bsky.app/profile/braintwin.bsky.social" target="_blank" rel="noopener" class="text-decoration-none" aria-label="BlueSky">
                <i class="bi bi-bluesky fs-4"></i>
              </a>
              <a href="https://github.com/braintwin2026/BRAINTWIN/" target="_blank" rel="noopener" class="text-decoration-none" aria-label="GitHub">
                <i class="bi bi-github fs-4"></i>
              </a>
              <a href="https://www.linkedin.com/company/braintwin" target="_blank" rel="noopener" class="text-decoration-none" aria-label="LinkedIn">
                <i class="bi bi-linkedin fs-4"></i>
              </a>
            </div>
          </div>
        </div>

        <div class="card border-0 bg-primary text-white">
          <div class="card-body">
            <h5 class="card-title text-white">Submit News</h5>
            <p class="small mb-3">BRAINTWIN members: Submit news items for publication.</p>
            <a href="{{ '/contact/' | relative_url }}" class="btn btn-light btn-sm">Contact Us</a>
          </div>
        </div>
      </div>
      <!-- /sidebar -->
    </div>
  </div>
</section>
