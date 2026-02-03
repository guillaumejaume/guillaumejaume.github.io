---
layout: default
title: "Guillaume Jaume, Ph.D."
---

<style>
/* FontAwesome CSS for icons */
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

/* Clean, simple landing page */
body, html {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: #333;
}

  .hero-section {
    background: linear-gradient(to right, #1e3a8a 0%, #1e40af 45%, #3b82f6 55%, #ffffff 70%);
    color: white;
    padding: 15px 20px;
    text-align: center;
  }

.hero-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 40px;
}

.hero-text {
  text-align: left;
  flex: 1;
}

.hero-title {
  font-size: 2.4rem;
  font-weight: 700;
  margin: 0 0 12px 0;
  line-height: 1.2;
}

.hero-subtitle {
  font-size: 1.2rem;
  margin: 0 0 12px 0;
  opacity: 0.9;
  font-weight: 500;
}



.hero-description {
  font-size: 1.1rem;
  margin: 0 0 25px 0;
  opacity: 0.85;
  line-height: 1.5;
  max-width: 500px;
}

.hero-buttons {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin-bottom: 15px;
}

.hero-btn {
  display: inline-block;
  padding: 10px 20px;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

  .hero-btn.primary {
    background: white;
    color: #1e3a8a;
  }

.hero-btn.primary:hover {
  background: #f8f9fa;
  transform: translateY(-2px);
}

.hero-btn.secondary {
  background: transparent;
  color: white;
  border-color: white;
}

  .hero-btn.secondary:hover {
    background: white;
    color: #1e3a8a;
    transform: translateY(-2px);
  }

.hero-image {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 15px;
}

.profile-photo {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid white;
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.hero-logo {
  object-fit: contain;
  border: none;
  background: transparent;
  box-shadow: none;
}

.hero-social-links {
  display: flex;
  gap: 15px;
  justify-content: center;
  flex-wrap: wrap;
}

.hero-social-link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  background: white;
  border-radius: 50%;
  text-decoration: none;
  color: #333;
  border: 1px solid #e9ecef;
  transition: all 0.3s ease;
}

.hero-social-link:hover {
  background: #f8f9fa;
  transform: translateY(-2px);
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

.hero-social-link i {
  font-size: 1.2rem;
}

/* Specific icon colors */
.hero-social-link .fa-github {
  color: #333;
}

.hero-social-link .fa-graduation-cap {
  color: #4285f4;
}

.hero-social-link .fa-linkedin {
  color: #0077b5;
}

.hero-social-link .fa-twitter {
  color: #1da1f2;
}

.hero-social-link .fa-x-twitter {
  color: #000000;
}

.x-logo {
  width: 16px;
  height: 16px;
  color: #000000;
}

.hero-email {
  margin-top: 10px;
  text-align: center;
}

.hero-email a {
  color: #1e3a8a;
  text-decoration: none;
  font-size: 1rem;
  font-weight: 500;
  transition: opacity 0.3s ease;
  font-family: 'Courier New', Courier, monospace;
  letter-spacing: 0.5px;
}

.hero-email a:hover {
  opacity: 1;
  text-decoration: underline;
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

/* Responsive design */
@media (max-width: 768px) {
  .hero-content {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-text {
    text-align: center;
  }
  
  .main-content {
    grid-template-columns: 1fr;
    gap: 30px;
  }
  
  .news-sidebar {
    position: static;
  }
  
  .hero-title {
    font-size: 2.2rem;
  }
  
  .hero-buttons {
    justify-content: center;
  }
}
</style>

<div class="hero-section">
  <div class="hero-content">
    <div class="hero-text">
      <h1 class="hero-title">Jaume Lab</h1>
      <p class="hero-subtitle">AI for Oncologic Pathology. Agentic, multimodal and foundational.</p>
      <div class="hero-buttons">
        <a href="/" class="hero-btn primary">Home</a>
        <a href="/people/" class="hero-btn secondary">People</a>
        <a href="/publications/" class="hero-btn secondary">Publications</a>
        <a href="/software/" class="hero-btn secondary">Software & Datasets</a>
        <a href="/talks/" class="hero-btn secondary">Talks</a>
      </div>
    </div>
    <div class="hero-image">
      <img src="/assets/people/lab_logo.png" alt="JaumeLab" class="profile-photo hero-logo">
      <div class="hero-social-links">
        <a href="https://github.com/guillaumejaume" target="_blank" class="hero-social-link">
          <i class="fab fa-github"></i>
        </a>
        <a href="https://scholar.google.com/citations?user=am5XqsQAAAAJ&hl=en" target="_blank" class="hero-social-link">
          <i class="fas fa-graduation-cap"></i>
        </a>
        <a href="https://www.linkedin.com/in/guillaume-jaume-455169104/" target="_blank" class="hero-social-link">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="https://twitter.com/GuillaumeJaume" target="_blank" class="hero-social-link">
          <svg class="x-logo" width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
            <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
          </svg>
        </a>
      </div>
      <div class="hero-email">
        <a href="mailto:guillaume.jaume@unil.ch">guillaume.jaume@unil.ch</a>
      </div>
    </div>
  </div>
</div>

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