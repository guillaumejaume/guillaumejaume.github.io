---
layout: default
title: "Software & Datasets"
permalink: /software/
---

<style>
/* FontAwesome CSS for icons */
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

/* Hero section styling */
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 25px 20px;
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
  display: flex;
  flex-direction: column;
  gap: 6px;
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
  color: #667eea;
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
  color: #667eea;
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
  color: white;
  text-decoration: none;
  font-size: 1rem;
  font-weight: 500;
  opacity: 0.9;
  transition: opacity 0.3s ease;
  font-family: 'Courier New', Courier, monospace;
  letter-spacing: 0.5px;
}

.hero-email a:hover {
  opacity: 1;
  text-decoration: underline;
}

/* Page content styling */
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

.section-header {
  text-align: center;
  margin-bottom: 50px;
  padding: 40px 20px;
  background: #f8f9fa;
  border-radius: 12px;
}

.section-header h2 {
  font-size: 2.5rem;
  color: #333;
  margin-bottom: 20px;
  border-bottom: 3px solid #667eea;
  padding-bottom: 15px;
  display: inline-block;
}

.section-description {
  font-size: 1.2rem;
  color: #555;
  line-height: 1.6;
  max-width: 800px;
  margin: 0 auto;
  font-style: italic;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 30px;
  margin-top: 40px;
}

.project-card {
  background: white;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  border: 1px solid #f0f0f0;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.project-type-container {
  display: flex;
  gap: 8px;
  margin-bottom: 15px;
  flex-wrap: wrap;
}

.project-type {
  display: inline-block;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  text-transform: uppercase;
}

.project-type.framework {
  background: #e3f2fd;
  color: #1976d2;
}

.project-type.tool {
  background: #f3e5f5;
  color: #7b1fa2;
}

.project-type.dataset {
  background: #e8f5e8;
  color: #388e3c;
}

.project-type.library {
  background: #fff3e0;
  color: #f57c00;
}

.project-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 10px;
  line-height: 1.4;
}

.project-description {
  font-size: 0.95rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 15px;
}

.github-badges {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  margin-bottom: 20px;
  align-items: center;
}

.github-badges img {
  height: 20px;
  border-radius: 4px;
  transition: transform 0.2s ease;
}

.github-badges img:hover {
  transform: scale(1.05);
}

.huggingface-badges {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  margin-bottom: 20px;
  align-items: center;
}

.huggingface-badges img {
  height: 20px;
  border-radius: 4px;
  transition: transform 0.2s ease;
}

.huggingface-badges img:hover {
  transform: scale(1.05);
}

.project-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.project-link {
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

.project-link:hover {
  background: #5a6fd8;
}

.coming-soon {
  text-align: center;
  padding: 60px 20px;
  background: #f8f9fa;
  border-radius: 12px;
  margin-top: 40px;
}

.coming-soon h3 {
  font-size: 1.8rem;
  color: #333;
  margin-bottom: 15px;
}

.coming-soon p {
  font-size: 1.1rem;
  color: #666;
  line-height: 1.6;
  max-width: 600px;
  margin: 0 auto;
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
  
  .hero-title {
    font-size: 2.2rem;
  }
  
  .hero-buttons {
    justify-content: center;
  }
  
  .projects-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero-section">
  <div class="hero-content">
    <div class="hero-text">
      <h1 class="hero-title"><a href="/" style="color: white; text-decoration: none;">Guillaume Jaume, Ph.D.</a></h1>
      <p class="hero-subtitle">Postdoctoral Researcher at Harvard Medical School<br>Incoming Tenure-track Assistant Professor at The University of Lausanne</p>
      <div class="hero-buttons">
        <a href="/" class="hero-btn secondary">Home</a>
        <a href="/publications/" class="hero-btn secondary">Publications</a>
        <a href="/software/" class="hero-btn primary">Software & Datasets</a>
        <a href="/talks/" class="hero-btn secondary">Talks</a>
      </div>
    </div>
    <div class="hero-image">
      <img src="/images/dali.jpeg" alt="Guillaume Jaume" class="profile-photo">
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
        <a href="mailto:gjaume@bwh.harvard.edu">gjaume@bwh.harvard.edu</a>
      </div>
    </div>
  </div>
</div>

<div class="page-content">
  


  <div class="projects-grid">
    <div class="project-card">
      <span class="project-type library">Library</span>
      <h3 class="project-title">Trident</h3>
      <p class="project-description">Reference library for histology image processing with integration of 25+ foundation models.</p>
      <div class="github-badges">
        <img src="https://img.shields.io/github/stars/mahmoodlab/trident?style=flat-square&labelColor=343b41" alt="GitHub stars">
        <img src="https://img.shields.io/github/languages/top/mahmoodlab/trident?style=flat-square&labelColor=343b41" alt="Top Language">
        <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?style=flat-square&labelColor=343b41" alt="License: CC BY-NC-SA 4.0">
        <img src="https://img.shields.io/github/last-commit/mahmoodlab/trident?style=flat-square&labelColor=343b41" alt="Last commit">
      </div>
      <div class="project-links">
        <a href="https://github.com/mahmoodlab/trident" target="_blank" class="project-link">Access</a>
      </div>
    </div>

    <div class="project-card">
      <div class="project-type-container">
        <span class="project-type dataset">Dataset</span>
        <span class="project-type library">Library</span>
      </div>
      <h3 class="project-title">Patho-Bench</h3>
      <p class="project-description">Largest public benchmark for pathology with 100+ curated tasks.</p>
      <div class="github-badges">
        <img src="https://img.shields.io/github/stars/mahmoodlab/patho-bench?style=flat-square&labelColor=343b41" alt="GitHub stars">
        <img src="https://img.shields.io/github/languages/top/mahmoodlab/patho-bench?style=flat-square&labelColor=343b41" alt="Top Language">
        <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?style=flat-square&labelColor=343b41" alt="License: CC BY-NC-SA 4.0">
        <img src="https://img.shields.io/github/last-commit/mahmoodlab/patho-bench?style=flat-square&labelColor=343b41" alt="Last commit">
      </div>
      <div class="huggingface-badges">
        <img src="https://img.shields.io/badge/HF-Downloads%3A%20839%2Fmonth-blue?style=flat-square&logo=huggingface" alt="Hugging Face Downloads">
        <img src="https://img.shields.io/badge/Tasks-95%20tasks-blue?style=flat-square" alt="95 Tasks">
      </div>
      <div class="project-links">
        <a href="https://github.com/mahmoodlab/patho-bench" target="_blank" class="project-link">Access</a>
      </div>
    </div>

    <div class="project-card">
      <div class="project-type-container">
        <span class="project-type dataset">Dataset</span>
        <span class="project-type library">Library</span>
      </div>
      <h3 class="project-title">HEST-1k</h3>
      <p class="project-description">The largest collection of 1k+ spatial transcriptomics paired with H&E whole-slide images and metadata.</p>
      <div class="github-badges">
        <img src="https://img.shields.io/github/stars/mahmoodlab/hest?style=flat-square&labelColor=343b41" alt="GitHub stars">
        <img src="https://img.shields.io/github/languages/top/mahmoodlab/hest?style=flat-square&labelColor=343b41" alt="Top Language">
        <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?style=flat-square&labelColor=343b41" alt="License: CC BY-NC-SA 4.0">
        <img src="https://img.shields.io/github/last-commit/mahmoodlab/hest?style=flat-square&labelColor=343b41" alt="Last commit">
      </div>
      <div class="huggingface-badges">
        <img src="https://img.shields.io/badge/HF-Downloads%3A%2011.8k%2Fmonth-blue?style=flat-square&logo=huggingface" alt="Hugging Face Downloads">
        <img src="https://img.shields.io/badge/Size-100B%3Cn%3C1T-blue?style=flat-square" alt="Dataset Size">
      </div>
      <div class="project-links">
        <a href="https://github.com/mahmoodlab/hest" target="_blank" class="project-link">Access</a>
      </div>
    </div>

    <div class="project-card">
      <span class="project-type library">Library</span>
      <h3 class="project-title">HistoCartography</h3>
      <p class="project-description">A collection of image-to-graph translation and state-of-the-art graph algorithms for facilitating interpretable entity-based analysis in digital pathology.</p>
      <div class="github-badges">
        <img src="https://img.shields.io/github/stars/histocartography/histocartography?style=flat-square&labelColor=343b41" alt="GitHub stars">
        <img src="https://img.shields.io/github/languages/top/histocartography/histocartography?style=flat-square&labelColor=343b41" alt="Top Language">
        <img src="https://img.shields.io/github/license/histocartography/histocartography?style=flat-square&labelColor=343b41" alt="License">
        <img src="https://img.shields.io/github/last-commit/histocartography/histocartography?style=flat-square&labelColor=343b41" alt="Last commit">
      </div>
      <div class="project-links">
        <a href="https://github.com/histocartography/histocartography" target="_blank" class="project-link">Access</a>
      </div>
    </div>

    <div class="project-card">
      <span class="project-type dataset">Dataset</span>
      <h3 class="project-title">BRACS</h3>
      <p class="project-description">BR<strong>e</strong>A<strong>st</strong> <strong>C</strong>arcinoma <strong>S</strong>ubtyping: A large cohort of H&E-stained histopathological images for fine-grained breast cancer subtyping.</p>
      <div class="project-links">
        <a href="https://www.bracs.icar.cnr.it/" target="_blank" class="project-link">Access</a>
      </div>
    </div>

    <div class="project-card">
      <span class="project-type dataset">Dataset</span>
      <h3 class="project-title">FUNSD</h3>
      <p class="project-description">A dataset for Form Understanding in Noisy Scanned Documents.</p>
      <div class="project-links">
        <a href="https://guillaumejaume.github.io/FUNSD/" target="_blank" class="project-link">Access</a>
      </div>
    </div>
  </div>
</div>
