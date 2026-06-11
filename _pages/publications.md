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
  background: var(--c-surface);
  border-radius: var(--radius-md);
  box-shadow: var(--shadow-card);
  border: 1px solid var(--c-border-soft);
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
  background: var(--c-surface-alt);
  color: var(--c-ink);
  font-size: 0.85rem;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  font-weight: 700;
  padding: 14px 16px;
  text-align: left;
  border-bottom: 1px solid var(--c-border);
  position: sticky;
  top: 0;
  z-index: 1;
}

.publications-table tbody tr {
  border-bottom: 1px solid var(--c-border-row);
}

.publications-table tbody tr:nth-child(even) {
  background: var(--c-surface-zebra);
}

.publications-table tbody tr:hover {
  background: var(--c-surface-hover);
}

.publications-table td {
  vertical-align: top;
  padding: 14px 16px;
  color: var(--c-ink);
  font-size: 0.95rem;
  line-height: 1.45;
}

.pub-year {
  white-space: nowrap;
  font-weight: 600;
  color: var(--c-text-soft);
}

.pub-type {
  white-space: nowrap;
}

.pub-title {
  font-weight: 600;
  color: var(--c-heading);
  min-width: 320px;
}

.pub-authors {
  color: var(--c-text-subtle);
  min-width: 360px;
}

.pub-venue {
  color: var(--c-text-soft);
  font-weight: 500;
  min-width: 200px;
}

.pub-link {
  color: var(--c-accent);
  text-decoration: none;
  font-weight: 600;
}

.pub-link:hover {
  text-decoration: underline;
}

.type-badge {
  display: inline-block;
  padding: 4px 10px;
  border-radius: var(--radius-pill);
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.02em;
}

.type-badge.journal { background: var(--badge-blue-bg); color: var(--badge-blue-fg); }
.type-badge.conference { background: var(--badge-purple-bg); color: var(--badge-purple-fg); }
.type-badge.review { background: var(--badge-teal-bg); color: var(--badge-teal-fg); }
.type-badge.preprint { background: var(--badge-green-bg); color: var(--badge-green-fg); }

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
    border: 1px solid var(--c-border);
    border-radius: var(--radius-md);
    margin: 0 0 10px 0;
    padding: 8px 0;
    background: var(--c-surface);
  }

  .publications-table tbody tr:nth-child(even) {
    background: var(--c-surface);
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
    color: var(--c-text-subtle);
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
            <td data-label="Year" class="pub-year">2026</td>
            <td data-label="Type" class="pub-type"><span class="type-badge review">Editorial</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://www.annalsofoncology.org/article/S0923-7534(26)00107-9/fulltext" target="_blank">Foundation models in pathology and the challenge of clinical time</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume</td>
            <td data-label="Venue / Status" class="pub-venue">Annals of Oncology</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2026</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">Preprint</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://arxiv.org/abs/2602.14177" target="_blank">Towards Spatial Transcriptomics-driven Pathology Foundation Models</a></td>
            <td data-label="Authors" class="pub-authors">Konstantin Hemker; Andrew H. Song; Cristina Almagro-Pérez; Guillaume Jaume; Sophia J. Wagner; Anurag Vaidya, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Preprint</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge conference">Conference (Oral)</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">BKVision: Automated Detection and Morphological Analysis of BK Virus in Renal Transplant Biopsies</a></td>
            <td data-label="Authors" class="pub-authors">Sharifa Sahai; Ana D. Ramos-Guerra; Cristina Almagro-Pérez; Guillaume Jaume; Andrew Zhang; Helmut Rennke, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">MICCAI</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">Preprint</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://arxiv.org/abs/2506.20964" target="_blank">Evidence-based diagnostic reasoning with multi-agent copilot for human pathology</a></td>
            <td data-label="Authors" class="pub-authors">Luca L. Weishaupt; Chengkuan Chen; Drew F. K. Williamson; Richard J. Chen; Guillaume Jaume; Tong Ding, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Preprint</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2025</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://arxiv.org/abs/2506.03373" target="_blank">A Foundation Model for Spatial Proteomics</a></td>
            <td data-label="Authors" class="pub-authors">Muhammad Shaban; Yuzhou Chang; Huaying Qiu; Yao Yu Yeo; Andrew H. Song; Guillaume Jaume, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">In Review</td>
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
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="https://arxiv.org/abs/2411.19666" target="_blank">Molecular-driven Foundation Model for Oncologic Pathology</a></td>
            <td data-label="Authors" class="pub-authors">Anurag Vaidya*; Andrew Zhang*; Guillaume Jaume*; Andrew H. Song; Tong Ding; Sophia J. Wagner, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">In Press</td>
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
            <td data-label="Authors" class="pub-authors">Andrew H. Song; Mane Williams; Drew F. K. Williamson; Sarah S.L. Chow; Guillaume Jaume; Gan Gao, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Cell</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge journal">Journal</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Examining Demographic Bias in Misdiagnosis by AI-Driven Computational Pathology Models</a></td>
            <td data-label="Authors" class="pub-authors">Anurag Vaidya; Richard J. Chen; Drew F. K. Williamson; Andrew H. Song; Guillaume Jaume; Yuzhe Yang, et al.</td>
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
            <td data-label="Authors" class="pub-authors">Richard J. Chen; Tong Ding; Ming Y. Lu; Drew F. K. Williamson; Guillaume Jaume; Andrew H. Song, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">Nature Medicine</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">Deep Learning-based Modeling for Preclinical Drug Safety Assessment</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Simone de Brot; Andrew H. Song; Drew F. K. Williamson; Lukas Oldenburg; Andrew Zhang, et al.</td>
            <td data-label="Venue / Status" class="pub-venue">In Review</td>
          </tr>
          <tr>
            <td data-label="Year" class="pub-year">2024</td>
            <td data-label="Type" class="pub-type"><span class="type-badge preprint">In Review</span></td>
            <td data-label="Title" class="pub-title"><a class="pub-link" href="#" target="_blank">AI-driven Discovery of Morphomolecular Signatures in Toxicology</a></td>
            <td data-label="Authors" class="pub-authors">Guillaume Jaume; Thomas Peeters; Andrew H. Song; Rowland Pettit; Drew F. K. Williamson; Lukas Oldenburg, et al.</td>
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
            <td data-label="Authors" class="pub-authors">Pushpak Pati; Guillaume Jaume; Zeineb Ayadi; Kevin Thandiackal; Behzad Bozorgtabar; Maria Gabrani, et al.</td>
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
