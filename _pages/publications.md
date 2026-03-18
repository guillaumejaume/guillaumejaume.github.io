---
layout: default
title: "Publications"
permalink: /publications/
---

<style>
.page-content {
  max-width: 1320px;
  margin: 0 auto;
  padding: 40px 20px;
}

.publications-table-wrap {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
  border: 1px solid #f0f0f0;
  overflow: hidden;
}

.publications-table-scroll {
  overflow-x: auto;
}

.publications-table {
  width: 100%;
  border-collapse: collapse;
  min-width: 1100px;
}

.publications-table thead th {
  background: #f6f8fc;
  color: #374151;
  font-size: 0.85rem;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  font-weight: 700;
  padding: 14px 16px;
  text-align: left;
  border-bottom: 1px solid #e5e7eb;
  position: sticky;
  top: 0;
  z-index: 1;
}

.publications-table tbody tr {
  border-bottom: 1px solid #eef1f5;
}

.publications-table tbody tr:nth-child(even) {
  background: #fbfcfe;
}

.publications-table tbody tr:hover {
  background: #f3f7ff;
}

.publications-table td {
  vertical-align: top;
  padding: 14px 16px;
  color: #374151;
  font-size: 0.95rem;
  line-height: 1.45;
}

.pub-year {
  white-space: nowrap;
  font-weight: 600;
  color: #4b5563;
}

.pub-type {
  white-space: nowrap;
}

.pub-title {
  font-weight: 600;
  color: #111827;
  min-width: 320px;
}

.pub-authors {
  color: #6b7280;
  min-width: 360px;
}

.pub-venue {
  color: #4b5563;
  font-weight: 500;
  min-width: 200px;
}

.pub-link {
  color: #1d4ed8;
  text-decoration: none;
  font-weight: 600;
}

.pub-link:hover {
  text-decoration: underline;
}

.type-badge {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 999px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.02em;
}

.type-badge.journal { background: #e3f2fd; color: #1976d2; }
.type-badge.conference { background: #f3e5f5; color: #7b1fa2; }
.type-badge.review { background: #d1ecf1; color: #0c5460; }
.type-badge.preprint { background: #e8f5e8; color: #388e3c; }

@media (max-width: 768px) {
  .page-content {
    padding: 24px 12px;
  }

  .publications-table {
    min-width: unset;
    border-collapse: separate;
  }

  .publications-table thead {
    display: none;
  }

  .publications-table tbody tr {
    display: block;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    margin: 0 0 10px 0;
    padding: 8px 0;
    background: white;
  }

  .publications-table tbody tr:nth-child(even) {
    background: white;
  }

  .publications-table td {
    display: block;
    border: none;
    padding: 6px 12px;
  }

  .publications-table td::before {
    display: block;
    content: attr(data-label);
    font-size: 0.74rem;
    font-weight: 700;
    text-transform: uppercase;
    color: #6b7280;
    margin-bottom: 3px;
  }
}
</style>

<div class="page-content">
  <div class="publications-table-wrap">
    <div class="publications-table-scroll">
      <table class="publications-table">
        <thead>
          <tr>
            <th>Year</th>
            <th>Type</th>
            <th>Title</th>
            <th>Authors</th>
            <th>Venue / Status</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://arxiv.org/abs/2411.19666" target="_blank">Molecular-driven Foundation Model for Oncologic Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Anurag Vaidya*; Andrew Zhang*; Guillaume Jaume*; Andrew H. Song; Tong Ding; Sophia J. Wagner, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">In Press</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Multimodal Whole Slide Foundation Model for Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Tong Ding; Sophia J. Wagner; Andrew H. Song; Richard J. Chen; Ming Y. Lu; Andrew Zhang, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Medicine</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">A Foundation Model for Spatial Proteomics</a></td>
            <td data-label="Authors" class="pub-authors">Muhammad Shaban; Yuzhou Chang; Huaying Qiu; Yao Yu Yeo; Andrew H. Song; Guillaume Jaume, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">In Review</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference (Oral)</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">BKVision: Automated Detection and Morphological Analysis of BK Virus in Renal Transplant Biopsies</a></td>
            <td data-label="Authors" class="pub-authors">Sharifa Sahai; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">MICCAI</td>
          </tr>

          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference (Spotlight)</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">HEST-1k: A Dataset Integrating Spatial Transcriptomics and Histology Image Analysis</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Paul Doucet; Andrew H. Song; Ming Y. Lu; Cristina Almagro-Pérez; Sophia J. Wagner, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">NeurIPS</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference (Oral)</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Transcriptomics-guided Slide Representation Learning in Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Lukas Oldenburg; Anurag Vaidya; Richard J. Chen; Drew F. K. Williamson; Thomas Peeters, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">CVPR</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Modeling Dense Multimodal Interactions Between Biological Pathways and Histology for Survival Prediction</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Anurag Vaidya; Richard J. Chen; Drew F. K. Williamson; Paul Pu Liang; Faisal Mahmood, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">CVPR</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Multimodal Prototyping for cancer survival prediction</a></td>
            <td data-label="Authors" class="pub-authors">Andrew H. Song; Richard J. Chen; Guillaume Jaume; Anurag Jayant Vaidya; Alexander Baras; Faisal Mahmood, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">ICML</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference (Oral)</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Morphological Prototyping for Unsupervised Slide Representation Learning in Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Andrew H. Song; Richard J. Chen; Tong Ding; Drew F. K. Williamson; Guillaume Jaume; Faisal Mahmood, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">CVPR</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Multistain Pretraining for Slide Representation Learning in Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Anurag Vaidya; Andrew Zhang; Andrew H. Song; Richard J. Chen; Sharifa Sahai, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">ECCV</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Analysis of 3D pathology samples using weakly supervised AI</a></td>
            <td data-label="Authors" class="pub-authors">Andrew H. Song; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">Cell</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Examining Demographic Bias in Misdiagnosis by AI-Driven Computational Pathology Models</a></td>
            <td data-label="Authors" class="pub-authors">Anurag Vaidya; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Medicine</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">A Visual-Language Foundation Model for Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Ming Y. Lu; Drew F. K. Williamson; Andrew H. Song; Richard J. Chen; Guillaume Jaume; Anurag Vaidya, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Medicine</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Towards a General-Purpose Foundation Model for Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Richard J. Chen; … Guillaume Jaume; Andrew H. Song; Ming Y. Lu; Anurag Vaidya, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Medicine</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Deep Learning-based Modeling for Preclinical Drug Safety Assessment</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">In Review</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">AI-driven Discovery of Morphomolecular Signatures in Toxicology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">In Review</td>
          </tr>

          <tr>
            <td data-label="Year" class="pub-year">2023</td>
            <td data-label="Type" class="pub-type"><span class="type-badge review">Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Artificial Intelligence for Digital and Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Andrew H. Song; Guillaume Jaume; Drew F. K. Williamson; Ming Y. Lu; Anurag Vaidya; Tiffany R. Miller, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Reviews Bioengineering</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2023</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Weakly Supervised Learning for Joint Whole-Slide Segmentation and Classification in Prostate Cancer</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; (lead); …</td>
            <td data-label="Venue / Status" class="pub-venue">Medical Image Analysis</td>
          </tr>

          <tr>
            <td data-label="Year" class="pub-year">2022</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Differentiable Zooming for Multiple Instance Learning on Whole-Slide Images</a></td>
            <td data-label="Authors" class="pub-authors">Kevin Thandiackal; Boqi Chen; Pushpak Pati; Guillaume Jaume; Drew F. K. Williamson; Maria Gabrani, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">ECCV</td>
          </tr>

          <tr>
            <td data-label="Year" class="pub-year">2021</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Hierarchical Graph Representations in Digital Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Pushpak Pati; Antonio Foncubierta-Rodríguez; Florinda Feroce; Anna Maria Anniciello; Tilman Rau, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Medical Image Analysis</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2021</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Quantifying Explainers of Graph Neural Networks in Computational Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Pushpak Pati; Behzad Bozorgtabar; Antonio Foncubierta-Rodríguez; Florinda Feroce; Anna Maria Anniciello, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">CVPR</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
