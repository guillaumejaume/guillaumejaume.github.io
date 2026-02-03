---
layout: default
title: "Publications"
permalink: /publications/
---

<style>
.page-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 20px;
}

.page-title {
  font-size: 2.5rem;
  font-weight: 700;
  color: #333;
  margin-bottom: 30px;
  text-align: center;
  border-bottom: 3px solid #667eea;
  padding-bottom: 15px;
}

.publications-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 30px;
  margin-top: 40px;
}

.publication-card {
  background: white;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  border: 1px solid #f0f0f0;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.publication-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.publication-type {
  display: inline-block;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  text-transform: uppercase;
  margin-bottom: 15px;
}

.publication-type.journal {
  background: #e3f2fd;
  color: #1976d2;
}

.publication-type.conference {
  background: #f3e5f5;
  color: #7b1fa2;
}

.publication-type.preprint {
  background: #e8f5e8;
  color: #388e3c;
}

.publication-type.review {
  background: #d1ecf1;
  color: #0c5460;
}

.publication-type-container {
  display: flex;
  gap: 8px;
  margin-bottom: 15px;
  flex-wrap: wrap;
  align-items: baseline;
}

.publication-type.book {
  background: #fff3e0;
  color: #f57c00;
}

.publication-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 10px;
  line-height: 1.4;
}

.publication-authors {
  font-size: 1rem;
  color: #666;
  margin-bottom: 8px;
  font-style: italic;
}

.publication-venue {
  font-size: 1rem;
  color: #666;
  margin-bottom: 8px;
  font-weight: 500;
}

.publication-year {
  font-size: 0.9rem;
  color: #888;
  margin-bottom: 15px;
}

.publication-description {
  font-size: 0.95rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 20px;
}

.badge {
  display: inline-block;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  text-transform: uppercase;
}

.badge.oral {
  background: #27ae60;
  color: white;
}

.badge.spotlight {
  background: #e74c3c;
  color: white;
}



.publication-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.publication-link {
  display: inline-block;
  padding: 8px 16px;
  background: #667eea;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: background 0.3s ease;
}

.publication-link:hover {
  background: #5a6fd8;
}

@media (max-width: 768px) {
  .publications-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="page-content">
  
  <div class="publications-grid">
    <!-- 2025 Publications -->
    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Molecular-driven Foundation Model for Oncologic Pathology</h3>
      <p class="publication-authors">Anurag Vaidya*; Andrew Zhang*; Guillaume Jaume*; Andrew H. Song; Tong Ding; Sophia J. Wagner, et al.</p>
      <p class="publication-venue"><strong>In Press</strong></p>
      <p class="publication-year">2025</p>
      <div class="publication-links">
        <a href="https://arxiv.org/abs/2411.19666" target="_blank" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Multimodal Whole Slide Foundation Model for Pathology</h3>
      <p class="publication-authors">Tong Ding; Sophia J. Wagner; Andrew H. Song; Richard J. Chen; Ming Y. Lu; Andrew Zhang, et al.</p>
      <p class="publication-venue"><strong>In Press</strong></p>
      <p class="publication-year">2025</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type preprint">In Review</span>
      <h3 class="publication-title">A Foundation Model for Spatial Proteomics</h3>
      <p class="publication-authors">Muhammad Shaban; Yuzhou Chang; Huaying Qiu; Yao Yu Yeo; Andrew H. Song; Guillaume Jaume, et al.</p>
      <p class="publication-year">2025</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
        <span class="badge oral">Oral</span>
      </div>
      <h3 class="publication-title">BKVision: Automated Detection and Morphological Analysis of BK Virus in Renal Transplant Biopsies</h3>
      <p class="publication-authors">Sharifa Sahai; (lead); …</p>
      <p class="publication-venue"><strong>MICCAI</strong></p>
      <p class="publication-year">2025</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <!-- 2024 Publications -->
    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
        <span class="badge spotlight">Spotlight</span>
      </div>
      <h3 class="publication-title">HEST-1k: A Dataset Integrating Spatial Transcriptomics and Histology Image Analysis</h3>
      <p class="publication-authors">Guillaume Jaume; Paul Doucet; Andrew H. Song; Ming Y. Lu; Cristina Almagro-Pérez; Sophia J. Wagner, et al.</p>
      <p class="publication-venue"><strong>NeurIPS</strong></p>
      <p class="publication-year">2024</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
        <span class="badge oral">Oral</span>
      </div>
      <h3 class="publication-title">Transcriptomics-guided Slide Representation Learning in Computational Pathology</h3>
      <p class="publication-authors">Guillaume Jaume; Lukas Oldenburg; Anurag Vaidya; Richard J. Chen; Drew F. K. Williamson; Thomas Peeters, et al.</p>
      <p class="publication-venue"><strong>CVPR</strong></p>
      <p class="publication-year">2024</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
      </div>
      <h3 class="publication-title">Modeling Dense Multimodal Interactions Between Biological Pathways and Histology for Survival Prediction</h3>
      <p class="publication-authors">Guillaume Jaume; Anurag Vaidya; Richard J. Chen; Drew F. K. Williamson; Paul Pu Liang; Faisal Mahmood, et al.</p>
      <p class="publication-venue"><strong>CVPR</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
      </div>
      <h3 class="publication-title">Multimodal Prototyping for cancer survival prediction</h3>
      <p class="publication-authors">Andrew H. Song; Richard J. Chen; Guillaume Jaume; Anurag Jayant Vaidya; Alexander Baras; Faisal Mahmood, et al.</p>
      <p class="publication-venue"><strong>ICML</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
        <span class="badge oral">Oral</span>
      </div>
      <h3 class="publication-title">Morphological Prototyping for Unsupervised Slide Representation Learning in Computational Pathology</h3>
      <p class="publication-authors">Andrew H. Song; Richard J. Chen; Tong Ding; Drew F. K. Williamson; Guillaume Jaume; Faisal Mahmood, et al.</p>
      <p class="publication-venue"><strong>CVPR</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type conference">Conference</span>
      <h3 class="publication-title">Multistain Pretraining for Slide Representation Learning in Pathology</h3>
      <p class="publication-authors">Guillaume Jaume; Anurag Vaidya; Andrew Zhang; Andrew H. Song; Richard J. Chen; Sharifa Sahai, et al.</p>
      <p class="publication-venue"><strong>ECCV</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Analysis of 3D pathology samples using weakly supervised AI</h3>
      <p class="publication-authors">Andrew H. Song; (lead); …</p>
      <p class="publication-venue"><strong>Cell</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Examining Demographic Bias in Misdiagnosis by AI-Driven Computational Pathology Models</h3>
      <p class="publication-authors">Anurag Vaidya; (lead); …</p>
      <p class="publication-venue"><strong>Nature Medicine</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">A Visual-Language Foundation Model for Computational Pathology</h3>
      <p class="publication-authors">Ming Y. Lu; Drew F. K. Williamson; Andrew H. Song; Richard J. Chen; Guillaume Jaume; Anurag Vaidya, et al.</p>
      <p class="publication-venue"><strong>Nature Medicine</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Towards a General-Purpose Foundation Model for Computational Pathology</h3>
      <p class="publication-authors">Richard J. Chen; … Guillaume Jaume; Andrew H. Song; Ming Y. Lu; Anurag Vaidya, et al.</p>
      <p class="publication-venue"><strong>Nature Medicine</strong></p>
      <p class="publication-year">2024</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type preprint">In Review</span>
      <h3 class="publication-title">Deep Learning-based Modeling for Preclinical Drug Safety Assessment</h3>
      <p class="publication-authors">Guillaume Jaume; (lead); …</p>
      <p class="publication-year">2024</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type preprint">In Review</span>
      <h3 class="publication-title">AI-driven Discovery of Morphomolecular Signatures in Toxicology</h3>
      <p class="publication-authors">Guillaume Jaume; (lead); …</p>
      <p class="publication-year">2024</p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <!-- 2023 Publications -->
    <div class="publication-card">
      <span class="publication-type review">Review</span>
      <h3 class="publication-title">Artificial Intelligence for Digital and Computational Pathology</h3>
      <p class="publication-authors">Andrew H. Song; Guillaume Jaume; Drew F. K. Williamson; Ming Y. Lu; Anurag Vaidya; Tiffany R. Miller, et al.</p>
      <p class="publication-venue"><strong>Nature Reviews Bioengineering</strong></p>
      <p class="publication-year">2023</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Weakly Supervised Learning for Joint Whole-Slide Segmentation and Classification in Prostate Cancer</h3>
      <p class="publication-authors">Guillaume Jaume; (lead); …</p>
      <p class="publication-venue"><strong>Medical Image Analysis</strong></p>
      <p class="publication-year">2023</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <!-- 2022 Publications -->
    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
      </div>
      <h3 class="publication-title">Differentiable Zooming for Multiple Instance Learning on Whole-Slide Images</h3>
      <p class="publication-authors">Kevin Thandiackal; Boqi Chen; Pushpak Pati; Guillaume Jaume; Drew F. K. Williamson; Maria Gabrani, et al.</p>
      <p class="publication-venue"><strong>ECCV</strong></p>
      <p class="publication-year">2022</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <!-- 2021 Publications -->
    <div class="publication-card">
      <span class="publication-type journal">Journal</span>
      <h3 class="publication-title">Hierarchical Graph Representations in Digital Pathology</h3>
      <p class="publication-authors">Guillaume Jaume; Pushpak Pati; Antonio Foncubierta-Rodríguez; Florinda Feroce; Anna Maria Anniciello; Tilman Rau, et al.</p>
      <p class="publication-venue"><strong>Medical Image Analysis</strong></p>
      <p class="publication-year">2021</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>

    <div class="publication-card">
      <div class="publication-type-container">
        <span class="publication-type conference">Conference</span>
      </div>
      <h3 class="publication-title">Quantifying Explainers of Graph Neural Networks in Computational Pathology</h3>
      <p class="publication-authors">Guillaume Jaume; Pushpak Pati; Behzad Bozorgtabar; Antonio Foncubierta-Rodríguez; Florinda Feroce; Anna Maria Anniciello, et al.</p>
      <p class="publication-venue"><strong>CVPR</strong></p>
      <p class="publication-year">2021</p>
      <p class="publication-description"></p>
      <div class="publication-links">
        <a href="#" class="publication-link">Access</a>
      </div>
    </div>
  </div>
</div>
