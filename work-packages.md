---
layout: default
title: Work Packages
permalink: /work-packages/
---

<!-- Page Header -->
<section class="page-header">
  <div class="container">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="{{ '/' | relative_url }}">Home</a></li>
        <li class="breadcrumb-item active" aria-current="page">Work Packages</li>
      </ol>
    </nav>
    <h1>Work Packages</h1>
  </div>
</section>

<!-- Introduction -->
<section class="section">
  <div class="container">
    <div class="row justify-content-center mb-5">
      <div class="col-lg-10">
        <p class="lead text-center">BRAINTWIN is organized into seven work packages (WPs) that break down the project into manageable tasks with clear objectives and deliverables. Each WP is led by a consortium partner with contributions from multiple institutions.</p>
      </div>
    </div>
    
    <!-- WP1 -->
    <div class="card mb-5 border-0 shadow-sm overflow-hidden" data-aos="fade-up" id="wp1">
      <div class="row g-0">
        <div class="col-md-4" style="background: linear-gradient(135deg, #1a5f7a 0%, #2e8ab8 100%);">
          <div class="p-4 h-100 d-flex flex-column justify-content-center text-white">
            <span class="badge bg-light text-primary mb-2" style="width: fit-content;">WP1</span>
            <h3 class="text-white">Data Integration & FAIR Platform</h3>
            <p class="small opacity-75 mb-0">Duration: Months 0-48</p>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card-body p-4">
            <p><strong>Lead:</strong> ICM (Paris Brain Institute) with HCL, CentraleSupelec, Ecole Polytechnique</p>
            <p><strong>Objective:</strong> Establish BRAINTWIN's data foundation by aggregating, harmonizing, and deploying a secure FAIR-compliant platform for multimodal brain tumor and SVD datasets.</p>
            
            <h6 class="mt-4">Key Tasks:</h6>
            <ul class="small">
              <li><strong>Task 1.1 - Multi-source Data Collection:</strong> Compile ~3,000 brain tumor cases and ~1,000 SVD cases with MRI, histopathology, molecular data, and clinical records</li>
              <li><strong>Task 1.2 - Data Harmonization:</strong> Standardize using BIDS for MRI and OMOP for clinical data; perform preprocessing, anonymization, and validation</li>
              <li><strong>Task 1.3 - FAIR Platform Development:</strong> Build secure federated platform with role-based access, GDPR compliance, and ethical governance</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    
    <!-- WP2 -->
    <div class="card mb-5 border-0 shadow-sm overflow-hidden" data-aos="fade-up" id="wp2">
      <div class="row g-0">
        <div class="col-md-4" style="background: linear-gradient(135deg, #134b5f 0%, #1a5f7a 100%);">
          <div class="p-4 h-100 d-flex flex-column justify-content-center text-white">
            <span class="badge bg-light text-primary mb-2" style="width: fit-content;">WP2</span>
            <h3 class="text-white">Multimodal AI Methods Development</h3>
            <p class="small opacity-75 mb-0">Duration: Months 0-48</p>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card-body p-4">
            <p><strong>Lead:</strong> CentraleSupelec (Prof. Vakalopoulou, Prof. Christodoulidis) with Polytechnique, INSA Lyon, ICM</p>
            <p><strong>Objective:</strong> Develop novel algorithms to extract features from each data modality and fuse them into an integrated model for clinically useful predictions.</p>
            
            <h6 class="mt-4">Key Tasks:</h6>
            <ul class="small">
              <li><strong>Task 2.1 - Multimodal Fusion Model:</strong> Develop architecture merging features across modalities using early/late fusion, cross-attention transformers, and dynamic fusion</li>
              <li><strong>Task 2.2 - Outcome Prediction:</strong> Train prediction heads for tumor subtype classification, survival time, and SVD risk with uncertainty estimation</li>
              <li><strong>Task 2.3 - Explainability:</strong> Implement XAI methods (Grad-CAM, attention heatmaps) for interpretable predictions</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    
    <!-- WP3 -->
    <div class="card mb-5 border-0 shadow-sm overflow-hidden" data-aos="fade-up" id="wp3">
      <div class="row g-0">
        <div class="col-md-4" style="background: linear-gradient(135deg, #159895 0%, #57c5b6 100%);">
          <div class="p-4 h-100 d-flex flex-column justify-content-center text-white">
            <span class="badge bg-light text-primary mb-2" style="width: fit-content;">WP3</span>
            <h3 class="text-white">Federated Learning & Privacy</h3>
            <p class="small opacity-75 mb-0">Duration: Months 6-48</p>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card-body p-4">
            <p><strong>Lead:</strong> Ecole Polytechnique (Prof. Dieuleveut) with Dr. Even, Prof. Bellet</p>
            <p><strong>Objective:</strong> Adapt federated learning methodology to multiple modalities and deploy a privacy-preserving FL framework across sites.</p>
            
            <h6 class="mt-4">Key Tasks:</h6>
            <ul class="small">
              <li><strong>Task 3.1 - FL Framework Setup:</strong> Configure federated platform (FedML/Flower) with secure server-client communication</li>
              <li><strong>Task 3.2 - Algorithmic Enhancements:</strong> Explore FedProx, FedDyn, meta-learning for data heterogeneity</li>
              <li><strong>Task 3.3 - Privacy Preservation:</strong> Implement differential privacy and robust aggregation techniques</li>
              <li><strong>Task 3.4 - Federated Training:</strong> Train BRAINTWIN model on distributed datasets and compare with centralized models</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    
    <!-- WP4 -->
    <div class="card mb-5 border-0 shadow-sm overflow-hidden" data-aos="fade-up" id="wp4">
      <div class="row g-0">
        <div class="col-md-4" style="background: linear-gradient(135deg, #2e8ab8 0%, #57c5b6 100%);">
          <div class="p-4 h-100 d-flex flex-column justify-content-center text-white">
            <span class="badge bg-light text-primary mb-2" style="width: fit-content;">WP4</span>
            <h3 class="text-white">Clinical Validation: Neuro-Oncology</h3>
            <p class="small opacity-75 mb-0">Duration: Months 12-48</p>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card-body p-4">
            <p><strong>Lead:</strong> ICM & Hospices Civils de Lyon (Dr. Alentorn, Prof. Ducray)</p>
            <p><strong>Objective:</strong> Rigorously evaluate the BRAINTWIN digital twin in brain tumor patients and demonstrate clinical utility.</p>
            
            <h6 class="mt-4">Key Tasks:</h6>
            <ul class="small">
              <li><strong>Task 4.1 - Retrospective Validation:</strong> Test model on retrospective cohorts, comparing against standard prognostic scores</li>
              <li><strong>Task 4.2 - Prospective Pilot:</strong> Deploy system in clinical workflow at partner hospitals</li>
              <li><strong>Task 4.3 - Biomarker Discovery:</strong> Uncover novel radiogenomic associations and prognostic biomarkers</li>
              <li><strong>Task 4.4 - Clinical Metrics:</strong> Evaluate health-economic impact and QALY gains</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    
    <!-- WP5 -->
    <div class="card mb-5 border-0 shadow-sm overflow-hidden" data-aos="fade-up" id="wp5">
      <div class="row g-0">
        <div class="col-md-4" style="background: linear-gradient(135deg, #0a1628 0%, #1a2744 100%);">
          <div class="p-4 h-100 d-flex flex-column justify-content-center text-white">
            <span class="badge bg-light text-primary mb-2" style="width: fit-content;">WP5</span>
            <h3 class="text-white">Clinical Validation: SVD</h3>
            <p class="small opacity-75 mb-0">Duration: Months 12-48</p>
          </div>
        </div>
        <div class="col-md-8">
          <div class="card-body p-4">
            <p><strong>Lead:</strong> ICM (Prof. Debette) with VBHI, Dr. Joliot</p>
            <p><strong>Objective:</strong> Test and validate the digital twin approach for cerebral small vessel diseases and neurodegenerative disorders.</p>
            
            <h6 class="mt-4">Key Tasks:</h6>
            <ul class="small">
              <li><strong>Task 5.1 - Cohort Analysis:</strong> Format cohort data and adapt model for stroke recurrence, cognitive decline prediction</li>
              <li><strong>Task 5.2 - Outcome Validation:</strong> Evaluate predictive performance vs Framingham Stroke Risk Score</li>
              <li><strong>Task 5.3 - International Cohorts:</strong> Test generalizability using ISGC/CHARGE international datasets</li>
              <li><strong>Task 5.4 - Prevention Strategies:</strong> Use digital twin to simulate interventions and identify personalized prevention</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    
    <!-- WP6 & WP7 -->
    <div class="row g-4">
      <div class="col-md-6" data-aos="fade-up">
        <div class="card h-100 border-0 shadow-sm" id="wp6">
          <div class="card-header text-white" style="background: linear-gradient(135deg, #64748b 0%, #94a3b8 100%);">
            <span class="badge bg-light text-primary">WP6</span>
            <h5 class="mb-0 mt-2 text-white">Dissemination & Exploitation</h5>
          </div>
          <div class="card-body">
            <p><strong>Lead:</strong> ICM (Dr. Alentorn) with all partners</p>
            <ul class="small mb-0">
              <li>Publications and conference presentations</li>
              <li>Open-source software toolkit release</li>
              <li>Stakeholder engagement and workshops</li>
              <li>Exploitation and sustainability planning</li>
            </ul>
          </div>
        </div>
      </div>
      
      <div class="col-md-6" data-aos="fade-up" data-aos-delay="100">
        <div class="card h-100 border-0 shadow-sm" id="wp7">
          <div class="card-header text-white" style="background: linear-gradient(135deg, #475569 0%, #64748b 100%);">
            <span class="badge bg-light text-primary">WP7</span>
            <h5 class="mb-0 mt-2 text-white">Project Management</h5>
          </div>
          <div class="card-body">
            <p><strong>Lead:</strong> ICM (Dr. Alentorn, Coordinator)</p>
            <ul class="small mb-0">
              <li>Steering Committee governance</li>
              <li>Reporting and documentation</li>
              <li>Risk management</li>
              <li>External Scientific Advisory Board</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
