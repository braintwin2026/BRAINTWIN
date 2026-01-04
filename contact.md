<!-- Contact Content -->
<section class="section" id="contact">
  <div class="container">

    <!-- IMPORTANT:
      The placement issues you see (Open Positions appearing as a “floating” block and overlapping/offset)
      almost always come from either:
        (1) missing/extra closing tags earlier, OR
        (2) a custom CSS rule on .section / .section-light / .container / .row that changes positioning.
      This chunk is fully balanced (all tags closed) and uses a clear 2-column grid + fixed widths.
    -->

    <div class="row g-4 align-items-start">

      <!-- LEFT COLUMN -->
      <div class="col-lg-7">
        <h2 class="section-title">Get in Touch</h2>
        <p class="lead mb-4">
          We welcome inquiries about collaboration, research opportunities, and general questions about the BRAINTWIN project.
        </p>

        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body p-4">
            <h5 class="mb-2"><i class="bi bi-envelope-fill text-primary me-2"></i>Email</h5>
            <p class="mb-0">
              For general inquiries:<br>
              <a href="mailto:braintwin@icm-institute.org">braintwin@icm-institute.org</a>
            </p>
          </div>
        </div>

        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body p-4">
            <h5 class="mb-2"><i class="bi bi-person-fill text-primary me-2"></i>Project Coordinator</h5>
            <p class="mb-0">
              <strong>Dr. Agusti Alentorn</strong><br>
              Paris Brain Institute (ICM)<br>
              <a href="mailto:agusti.alentorn@icm-institute.org">agusti.alentorn@icm-institute.org</a>
            </p>
          </div>
        </div>

        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body p-4">
            <h5 class="mb-2"><i class="bi bi-geo-alt-fill text-primary me-2"></i>Address</h5>
            <p class="mb-0">
              <strong>Paris Brain Institute (ICM)</strong><br>
              Hôpital Pitié-Salpêtrière<br>
              47 Boulevard de l’Hôpital<br>
              75013 Paris, France
            </p>
            <div class="mt-3">
              <a class="btn btn-sm btn-outline-primary"
                 href="https://www.google.com/maps/search/?api=1&query=Paris+Brain+Institute+ICM+47+Boulevard+de+l%27Hopital+75013+Paris"
                 target="_blank" rel="noopener">
                <i class="bi bi-map me-1"></i>Open in Maps
              </a>
            </div>
          </div>
        </div>

        <div class="card border-0 shadow-sm">
          <div class="card-body p-4">
            <h5 class="mb-2"><i class="bi bi-share-fill text-primary me-2"></i>Follow Us</h5>
            <div class="d-flex gap-3">
              <a href="https://github.com/BRAINTWIN" target="_blank" rel="noopener" class="text-decoration-none">
                <i class="bi bi-github fs-4"></i>
              </a>
              <a href="https://bsky.app/profile/braintwin.bsky.social" target="_blank" rel="noopener" class="text-decoration-none">
                <i class="bi bi-bluesky fs-4"></i>
              </a>
              <a href="https://www.linkedin.com/company/braintwin" target="_blank" rel="noopener" class="text-decoration-none">
                <i class="bi bi-linkedin fs-4"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
      <!-- /LEFT COLUMN -->

      <!-- RIGHT COLUMN -->
      <div class="col-lg-5">

        <!-- QUICK LINKS + CONTACTS -->
        <div class="card border-0 shadow-sm mb-4">
          <div class="card-body p-4">
            <h5 class="card-title mb-4">Quick Links</h5>

            <div class="mb-4">
              <h6 class="mb-2"><i class="bi bi-people me-2 text-primary"></i>Collaboration</h6>
              <p class="small text-muted mb-2">
                Interested in collaborating on digital twin research for neurology?
              </p>
              <a href="mailto:braintwin@icm-institute.org" class="btn btn-sm btn-outline-primary">Contact Us</a>
            </div>

            <hr>

            <h6 class="mb-2"><i class="bi bi-buildings me-2 text-primary"></i>Partner Institution Contacts</h6>
            <p class="small text-muted mb-3">
              Each contact is listed by name, followed by the shorthand <strong>X<sub>i</sub> Y<sub>i</sub></strong>.
              See the note below for how to construct institutional email addresses.
            </p>

            <ul class="list-unstyled small mb-0">
              <li class="mb-3">
                <strong>Paris Brain Institute (ICM):</strong><br>
                Agusti Alentorn — X<sub>1</sub> Y<sub>1</sub>
              </li>

              <li class="mb-3">
                <strong>CentraleSupélec, Univ. Paris-Saclay:</strong><br>
                Maria Vakalopoulou — X<sub>1</sub> Y<sub>1</sub><br>
                Stergios Christodoulidis — X<sub>2</sub> Y<sub>2</sub>
              </li>

              <li class="mb-3">
                <strong>École Polytechnique:</strong><br>
                Aymeric Dieuleveut — X<sub>1</sub> Y<sub>1</sub><br>
                Vicky Kalogeiton — X<sub>2</sub> Y<sub>2</sub><br>
                Maks Ovsjanikov — X<sub>3</sub> Y<sub>3</sub>
              </li>

              <li class="mb-3">
                <strong>Hospices Civils de Lyon (HCL):</strong><br>
                François Ducray — X<sub>1</sub> Y<sub>1</sub>
              </li>

              <li class="mb-3">
                <strong>CREATIS-INSA Lyon:</strong><br>
                Carole Lartizien — X<sub>1</sub> Y<sub>1</sub>
              </li>

              <li class="mb-0">
                <strong>VBHI Bordeaux:</strong><br>
                Marc Joliot — X<sub>1</sub> Y<sub>1</sub>
              </li>
            </ul>

            <div class="mt-4 small text-muted">
              <strong>How to email contacts:</strong><br>
              Use the format <code>x.y@institution</code>, where:
              <ul class="mb-0">
                <li><strong>X</strong> = given name (first name, lowercase)</li>
                <li><strong>Y</strong> = family name (surname, lowercase)</li>
                <li><strong>institution</strong> = the institution’s email domain (see below)</li>
              </ul>

              <div class="mt-3">
                <strong>Institution email domains:</strong>
                <ul class="mb-0">
                  <li>Paris Brain Institute (ICM): <code>icm-institute.org</code></li>
                  <li>CentraleSupélec, Univ. Paris-Saclay: <code>centralesupelec.fr</code></li>
                  <li>École Polytechnique: <code>polytechnique.edu</code></li>
                  <li>Hospices Civils de Lyon (HCL): <code>chu-lyon.fr</code></li>
                  <li>CREATIS-INSA Lyon: <code>creatis.insa-lyon.fr</code></li>
                  <li>VBHI Bordeaux: <code>u-bordeaux.fr</code></li>
                </ul>
              </div>

              <p class="mt-3 mb-0">
                Example: <code>x.y@institution</code> (replace <code>x</code>, <code>y</code>, and <code>institution</code> accordingly).
              </p>
            </div>
          </div>
        </div>

        <!-- OPEN POSITIONS (RIGHT COLUMN, FIXED WIDTH, NO CENTERING THAT BREAKS FLOW) -->
        <div class="card border-0 shadow-sm" id="positions">
          <div class="card-body p-4">
            <div class="d-flex align-items-center justify-content-between mb-3">
              <h5 class="mb-0"><i class="bi bi-briefcase me-2 text-primary"></i>Open Positions</h5>
              <span class="badge bg-warning text-dark">Coming soon</span>
            </div>

            <div class="alert alert-info small mb-3 d-flex gap-2 align-items-start">
              <i class="bi bi-info-circle mt-1"></i>
              <div>
                <strong>Current status:</strong> positions are being finalised. If you are interested, you can already reach out to the coordinator and we will
                route your enquiry to the relevant partner.
              </div>
            </div>

            <!-- Position 1 -->
            <div class="border rounded-3 p-3 mb-3">
              <div class="d-flex justify-content-between align-items-start gap-3">
                <div class="flex-grow-1">
                  <div class="d-flex flex-wrap gap-2 mb-2">
                    <span class="badge bg-success">PhD</span>
                    <span class="badge bg-warning text-dark">Coming soon</span>
                  </div>
                  <h6 class="mb-1">Multimodal Deep Learning for Brain Tumors</h6>
                  <p class="text-muted small mb-0">
                    <i class="bi bi-geo-alt me-1"></i>CentraleSupélec, Univ. Paris-Saclay
                  </p>
                </div>
                <a class="btn btn-sm btn-outline-primary"
                   href="mailto:braintwin@icm-institute.org?subject=BRAINTWIN%20-%20Interest%20in%20PhD%20(Multimodal%20DL)">
                  <i class="bi bi-envelope me-1"></i>Express interest
                </a>
              </div>
            </div>

            <!-- Position 2 -->
            <div class="border rounded-3 p-3 mb-3">
              <div class="d-flex justify-content-between align-items-start gap-3">
                <div class="flex-grow-1">
                  <div class="d-flex flex-wrap gap-2 mb-2">
                    <span class="badge bg-success">PhD</span>
                    <span class="badge bg-warning text-dark">Coming soon</span>
                  </div>
                  <h6 class="mb-1">Federated Learning for Medical AI</h6>
                  <p class="text-muted small mb-0">
                    <i class="bi bi-geo-alt me-1"></i>École Polytechnique, Paris
                  </p>
                </div>
                <a class="btn btn-sm btn-outline-primary"
                   href="mailto:braintwin@icm-institute.org?subject=BRAINTWIN%20-%20Interest%20in%20PhD%20(Federated%20Learning)">
                  <i class="bi bi-envelope me-1"></i>Express interest
                </a>
              </div>
            </div>

            <!-- Position 3 -->
            <div class="border rounded-3 p-3">
              <div class="d-flex justify-content-between align-items-start gap-3">
                <div class="flex-grow-1">
                  <div class="d-flex flex-wrap gap-2 mb-2">
                    <span class="badge bg-primary">Postdoc</span>
                    <span class="badge bg-warning text-dark">Coming soon</span>
                  </div>
                  <h6 class="mb-1">Clinical Validation of Digital Twins</h6>
                  <p class="text-muted small mb-0">
                    <i class="bi bi-geo-alt me-1"></i>Paris Brain Institute (ICM)
                  </p>
                </div>
                <a class="btn btn-sm btn-outline-primary"
                   href="mailto:braintwin@icm-institute.org?subject=BRAINTWIN%20-%20Interest%20in%20Postdoc%20(Clinical%20Validation)">
                  <i class="bi bi-envelope me-1"></i>Express interest
                </a>
              </div>
            </div>

            <div class="mt-4">
              <a href="mailto:braintwin@icm-institute.org?subject=BRAINTWIN%20-%20General%20Interest%20(Open%20Positions)"
                 class="btn btn-primary w-100">
                <i class="bi bi-envelope me-2"></i>Contact the consortium
              </a>
              <p class="small text-muted text-center mt-2 mb-0">
                Please include a short CV and a few lines about your interests.
              </p>
            </div>

          </div>
        </div>

      </div>
      <!-- /RIGHT COLUMN -->

    </div>
  </div>
</section>

<!-- OPTIONAL (recommended) CSS PATCH:
     Put this in assets/css/style.css (NOT inline) to prevent any “floating/overlap” effects
     if your theme has aggressive positioning rules.
-->
<!--
.section { position: relative; z-index: 1; }
#positions { position: relative; z-index: 1; }
.site-footer { position: relative; z-index: 2; }
-->
