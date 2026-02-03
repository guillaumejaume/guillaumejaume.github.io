---
layout: default
title: "Guillaume Jaume, Ph.D."
---

<style>
body, html {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: #333;
}

.main-content {
  max-width: 1400px;
  margin: 0 auto;
  padding: 8px 20px;
  display: grid;
  grid-template-columns: 1fr 400px;
  gap: 50px;
}

.about-section {
  background: white;
  padding: 20px 40px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  border: 1px solid #f0f0f0;
  min-height: 250px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}

.about-section h2 {
  margin: 0 0 15px 0;
  color: #333;
  font-size: 1.8rem;
  border-bottom: 2px solid #007bff;
  padding-bottom: 10px;
}

.about-section p {
  margin: 0 0 15px 0;
  line-height: 1.6;
  color: #555;
  font-size: 0.9rem;
}

.about-section p:last-child {
  margin-bottom: 0;
}

.join-us-section {
  background: white;
  padding: 15px 30px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  border: 1px solid #f0f0f0;
  margin-top: 8px;
  min-height: 200px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}

.join-us-section h2 {
  margin: 0 0 15px 0;
  color: #333;
  font-size: 1.8rem;
  border-bottom: 2px solid #007bff;
  padding-bottom: 10px;
}

.join-us-section p {
  margin: 0 0 10px 0;
  line-height: 1.6;
  color: #555;
  font-size: 0.9rem;
}

.join-us-section ul li {
  margin-bottom: 6px;
  line-height: 1.4;
}

.news-sidebar {
  background: white;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  border: 1px solid #f0f0f0;
  height: 600px;
  position: sticky;
  top: 20px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}

.news-content {
  flex: 1;
  overflow-y: auto;
  padding-right: 10px;
}

.news-content::-webkit-scrollbar {
  width: 6px;
}

.news-content::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}

.news-content::-webkit-scrollbar-thumb {
  background: #c1c1c1;
  border-radius: 3px;
}

.news-content::-webkit-scrollbar-thumb:hover {
  background: #a8a8a8;
}

.news-sidebar h3 {
  margin: 0 0 20px 0;
  color: #333;
  font-size: 1.5rem;
  border-bottom: 2px solid #007bff;
  padding-bottom: 10px;
}

.news-item {
  padding: 8px 0;
  border-bottom: 1px solid #f0f0f0;
}

.news-item:last-child {
  border-bottom: none;
}

.news-item.featured {
  background: white;
  padding: 12px;
  border-radius: 8px;
  margin-bottom: 12px;
}

.news-item.featured.red {
  background: #fff5f5;
  border-left: 4px solid #e74c3c;
}

.badge {
  display: inline-block;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 0.7rem;
  font-weight: 600;
  text-transform: uppercase;
}

.badge.spotlight {
  background: #e74c3c;
  color: white;
}

.badge.oral {
  background: #27ae60;
  color: white;
}

.news-date {
  display: block;
  font-size: 0.85rem;
  color: #007bff;
  font-weight: 600;
  margin-bottom: 4px;
}

.news-item p {
  margin: 0;
  line-height: 1.5;
  color: #555;
  font-size: 0.85rem;
}

.news-item a {
  color: #007bff;
  text-decoration: none;
}

.news-item a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .main-content {
    grid-template-columns: 1fr;
    gap: 30px;
  }
  .news-sidebar {
    position: static;
  }
}
</style>

<div class="main-content">
  <div class="main-content-left">
    <section class="about-section">
      <h2>About</h2>
      <p>The <strong>JaumeLab</strong> is launching in February 2026 at the <a href="https://www.unil.ch/dof/en/home.html" target="_blank">Department of Oncology</a> at the <strong>University of Lausanne (UNIL)</strong>.</p>
      <p>We work at the intersection of <em>artificial intelligence, pathology, and oncology</em>. Our research focuses on <strong>agentic AI, biomarker discovery, and multimodal learning </strong> for pathology.</p>
      <p>We keep <strong>strong ties</strong> to <strong>Harvard Medical School, Mass General Brigham, EPFL, and ETH Zurich</strong>.</p>
    </section>
    
    <section class="join-us-section">
      <h2>Join Us</h2>
      <p>We are looking for <strong>PhD students, postdocs, and interns</strong> to build the next generation of AI for oncology and pathology. You will:</p>
      <ul>
        <li>Work on the <strong>latest AI research</strong> with <em>direct applications in cancer and medicine</em>.</li>
        <li>Contribute to <strong>open science</strong> with <em>tools, software and AI models</em> that will shape the future of computational oncology.</li>
        <li>Collaborate <strong>internationally</strong> with <em>leading institutions and labs</em>.</li>
      </ul>
      <p><em>We'd love to hear from you.</em></p>
      <p><a href="https://docs.google.com/forms/d/1TQEHI8mXbt4kanYdh-j3UYgLLWpcZR8Cr3voVxDKmTQ/edit" target="_blank" style="background: #1e3a8a; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; font-weight: 600; display: inline-block; margin-top: 10px;">Apply Now →</a></p>
    </section>
  </div>

  <aside class="news-sidebar">
    <h3>News</h3>
    <div class="news-content">
      
        <div class="news-item featured">
          <span class="news-date">Feb'26</span>
          <p><strong>Welcome Alexandre and Hong!</strong> Excited to welcome <strong>Alexandre de Skowronski</strong> and <strong>Hong Liu</strong> as the first members of the lab.</p>
        </div>
      
        <div class="news-item featured red">
          <span class="news-date">Feb'26</span>
          <p><strong>The lab officially launches!</strong> Our lab is now officially starting!</p>
        </div>
            
        <div class="news-item featured red">
          <span class="news-date">September'25</span>
          <p><strong>ERC Starting Grant Awarded!</strong> We are honored to receive a €1.7M ERC Starting Grant to pursue five years of research on agentic AI and structure segmentation in pathology.</p>
        </div>
      
      <div class="news-item featured red">
        <span class="news-date">August'25</span>
        <p>Announcing <strong>KRONOS</strong>, a foundation model for spatial proteomics</p>
        <p><a href="https://arxiv.org/abs/2506.03373" target="_blank">Preprint</a> | <a href="https://github.com/mahmoodlab/KRONOS/" target="_blank">Code</a> | <a href="https://huggingface.co/MahmoodLab/KRONOS" target="_blank">Model</a></p>
      </div>
      
      <div class="news-item featured red">
        <span class="news-date">April'25</span>
        <p><strong>TRIDENT</strong> is out! Checkout our latest library for processing whole-slide images with foundation models!</p>
        <p><a href="https://github.com/mahmoodlab/trident" target="_blank">Code</a></p>
      </div>
      
      <div class="news-item featured">
        <span class="news-date">March'25</span>
        <p>Announcing <strong>Patho-Bench</strong>, our new set of 100+ tasks for benchmarking AI models for pathology</p>
        <p><a href="https://github.com/mahmoodlab/patho-bench" target="_blank">Code</a> | <a href="https://huggingface.co/datasets/MahmoodLab/Patho-Bench" target="_blank">Dataset</a></p>
      </div>
      
      <div class="news-item featured">
        <span class="news-date">March'25</span>
        <p>New preprint on 3D modeling of spatial transcriptomics data</p>
        <p><a href="https://arxiv.org/abs/2502.17761" target="_blank">Preprint</a></p>
      </div>
      
      <div class="news-item featured">
        <span class="news-date">March'25</span>
        <p>New preprint for whole-slide image classification with agentic AI</p>
        <p><a href="https://arxiv.org/abs/2506.20964" target="_blank">Preprint</a></p>
      </div>
      
      <div class="news-item featured red">
        <span class="news-date">Oct'24</span>
        <p><strong>HEST</strong> to appear at <a href="https://github.com/mahmoodlab/HEST" target="_blank"><strong>NeurIPS</strong></a> will be a <span class="badge spotlight">Spotlight</span> (top 2.0% of submissions).</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">July'24</span>
        <p>Announcing <strong>TRACE</strong>, our new <a href="https://www.biorxiv.org/content/10.1101/2024.07.20.604430v1.abstract" target="_blank"><strong>preprint</strong></a> on toxicity assessment and drug safety!</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">July'24</span>
        <p>Announcing <strong>GEESE</strong>, our new <a href="https://www.biorxiv.org/content/10.1101/2024.07.19.604355v1.abstract" target="_blank"><strong>preprint</strong></a> for multimodal toxicity identification!</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">July'24</span>
        <p>Announcing <strong>MADELEINE</strong> to appear at <a href="https://github.com/mahmoodlab/MADELEINE/tree/main" target="_blank"><strong>ECCV</strong></a>, a multimodal pretraining strategy for slide representation learning.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">May'24</span>
        <p>Announcing <strong>TriPath</strong> published in <a href="https://www.cell.com/cell/abstract/S0092-8674(24)00351-9" target="_blank"><strong>Cell</strong></a>, the first deep learning framework for 3D pathology.</p>
      </div>
      
      <div class="news-item featured red">
        <span class="news-date">May'24</span>
        <p><strong>TANGLE</strong> to appear at <a href="https://github.com/mahmoodlab/TANGLE" target="_blank"><strong>CVPR</strong></a> will be an <span class="badge oral">Oral</span> (top 0.7% of submissions).</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">May'24</span>
        <p>Announcing <strong>MMP</strong> to appear at <a href="https://github.com/mahmoodlab/MMP/tree/main" target="_blank"><strong>ICML</strong></a>, a multimodal model for survival outcome prediction.</p>
    </div>
      
      <div class="news-item">
        <span class="news-date">April'24</span>
        <p>New <a href="https://www.nature.com/articles/s41591-024-02885-z" target="_blank"><strong>Nature Medicine</strong></a> study on fairness in computational pathology.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">March'24</span>
        <p>Announcing <strong>UNI</strong> published in <a href="https://www.nature.com/articles/s41591-024-02857-3" target="_blank"><strong>Nature Medicine</strong></a>, a generic-purpose foundation model for histology.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">March'24</span>
        <p>Announcing <strong>CONCH</strong> published in <a href="https://www.nature.com/articles/s41591-024-02856-4" target="_blank"><strong>Nature Medicine</strong></a>, a visual-language model for histology.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">Feb'24</span>
        <p>Announcing <strong>SURVPATH</strong> to appear at <a href="https://github.com/mahmoodlab/SurvPath" target="_blank"><strong>CVPR</strong></a>, multimodal model for survival outcome prediction.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">Feb'24</span>
        <p>Announcing <strong>PANTHER</strong> to appear at <a href="https://github.com/mahmoodlab/PANTHER" target="_blank"><strong>CVPR</strong></a>, a model for survival prediction.</p>
      </div>
      
      <div class="news-item">
        <span class="news-date">June'23</span>
        <p>New <a href="https://www.nature.com/articles/s44222-023-00096-8" target="_blank"><strong>Nature Reviews Bioengineering</strong></a> article on AI for digital and computational Pathology.</p>
      </div>
    </div>
  </aside>
</div> 