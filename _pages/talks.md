---
layout: default
title: "Communication"
permalink: /talks/
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
  max-width: 1350px;
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

.talks-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin-top: 40px;
}

.talk-card {
  background: white;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  border: 1px solid #f0f0f0;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.talk-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.talk-type {
  display: inline-block;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  text-transform: uppercase;
  margin-bottom: 15px;
}

.talk-type.conference {
  background: #e3f2fd;
  color: #1976d2;
}

.talk-type.workshop {
  background: #f3e5f5;
  color: #7b1fa2;
}

.talk-type.invited {
  background: #e3f2fd;
  color: #1976d2;
}

.talk-type.keynote {
  background: #fff3e0;
  color: #f57c00;
}

.talk-type.internal {
  background: #f3e5f5;
  color: #7b1fa2;
}

.talk-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 10px;
  line-height: 1.4;
}

.talk-venue {
  font-size: 1rem;
  color: #666;
  margin-bottom: 8px;
  font-weight: 500;
}

.talk-date {
  font-size: 0.9rem;
  color: #888;
  margin-bottom: 15px;
}

.talk-description {
  font-size: 0.95rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 20px;
}

.talk-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.talk-link {
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

.talk-link:hover {
  background: #5a6fd8;
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
  
  .talks-grid {
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
        <a href="/software/" class="hero-btn secondary">Software & Datasets</a>
        <a href="/talks/" class="hero-btn primary">Talks</a>
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
        <a href="mailto:guillaume.jaume@unil.ch">guillaume.jaume@unil.ch</a>
      </div>
    </div>
  </div>
</div>

<div class="page-content">
  
  <div class="talks-grid">
    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Toward Generalist AI Models in Pathology</h3>
      <p class="talk-venue">AbbVie, Chicago</p>
      <p class="talk-date">May 2025</p>
      <p class="talk-description">Invited by Dr. Sara Yarmohammadi</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Toward Generalist AI Models in Pathology</h3>
      <p class="talk-venue">Microsoft Research, Boston</p>
      <p class="talk-date">April 2025</p>
      <p class="talk-description">Invited by Dr. Kristen Severson</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Advancing Translational Research with AI in Oncologic Pathology</h3>
      <p class="talk-venue">CRUK, University of Cambridge</p>
      <p class="talk-date">March 2025</p>
      <p class="talk-description">Invited by Prof. Florian Markowetz</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">AI for Computational Toxicologic Pathology</h3>
      <p class="talk-venue">Novartis, Boston</p>
      <p class="talk-date">March 2025</p>
      <p class="talk-description">Invited by the Digital Pathology and Image Analysis Interest Group</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Bringing Spatial Transcriptomics into The World of Deep Learning</h3>
      <p class="talk-venue">University of Sydney</p>
      <p class="talk-date">March 2025</p>
      <p class="talk-description">Invited by SPDS Statistical Bioinformatics Seminar</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Scaling Spatial Transcriptomics and Histology with HEST</h3>
      <p class="talk-venue">Owkin, Paris</p>
      <p class="talk-date">December 2024</p>
      <p class="talk-description">Invited by Alexandre Filliot</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">AI for Preclinical Drug Safety Assessment</h3>
      <p class="talk-venue">Roche, Basel</p>
      <p class="talk-date">November 2024</p>
      <p class="talk-description">Invited by Dr. Kevin Thandiackal</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Multimodal Representation Learning in AI for Pathology</h3>
      <p class="talk-venue">Lunit, Seoul</p>
      <p class="talk-date">September 2024</p>
      <p class="talk-description">Invited by Dr. Sergio Pereira</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">3D Computational Pathology: Towards Enhanced Patient Prognostication</h3>
      <p class="talk-venue">UniBe, Bern</p>
      <p class="talk-date">May 2024</p>
      <p class="talk-description">Invited by Prof. Inti Zlobek</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Towards General-Purpose AI Models for Histology</h3>
      <p class="talk-venue">CHUV, Lausanne</p>
      <p class="talk-date">May 2024</p>
      <p class="talk-description">Invited by Prof. Raphael Gottardo</p>
    </div>

    <div class="talk-card">
      <span class="talk-type keynote">Keynote</span>
      <h3 class="talk-title">Deep Learning for Pathology Image Analysis</h3>
      <p class="talk-venue">PariSanté Campus, Paris</p>
      <p class="talk-date">July 2023</p>
      <p class="talk-description">Keynote speaker, AI4Health Summer School</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Latest trends in Computational Pathology</h3>
      <p class="talk-venue">University of Bern, Bern</p>
      <p class="talk-date">July 2023</p>
      <p class="talk-description">Invited by Prof. Inti Zlobek</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">A Tour of Computational Pathology: Methods and Applications</h3>
      <p class="talk-venue">UC Berkeley, Berkeley</p>
      <p class="talk-date">November 2022</p>
      <p class="talk-description">Invited by Prof. Iain Carmichael</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Interpretable Deep Learning in Computational Pathology</h3>
      <p class="talk-venue">Dana-Farber Cancer Institute, Boston</p>
      <p class="talk-date">September 2022</p>
      <p class="talk-description">Invited by Prof. Eliezer Van Allen</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Graph Representation Learning in Computational Pathology</h3>
      <p class="talk-venue">Symposium on DigPath in the DACH Region, Bern</p>
      <p class="talk-date">February 2022</p>
      <p class="talk-description">Invited by Prof. Inti Zlobek</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">HistoCartography: Graph representations and models in Computational Pathology</h3>
      <p class="talk-venue">Tissue Image Analytics Centre, Warwick</p>
      <p class="talk-date">October 2021</p>
      <p class="talk-description">Invited by Prof. Nasir Rajpoot</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Graph Representations and Models in Digital Pathology</h3>
      <p class="talk-venue">Charité University Hospital, Berlin</p>
      <p class="talk-date">October 2021</p>
      <p class="talk-description"></p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Weakly-Supervised Learning for Whole-Slide-Image Segmentation</h3>
      <p class="talk-venue">PathAI, New York</p>
      <p class="talk-date">July 2021</p>
      <p class="talk-description"></p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">A Graph Network Tour of Computational Pathology</h3>
      <p class="talk-venue">Harvard Medical School, Boston</p>
      <p class="talk-date">July 2021</p>
      <p class="talk-description">Invited by Prof. Faisal Mahmood</p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Computational Pathology: Building Interpretable AI at Scale</h3>
      <p class="talk-venue">Lausanne University Hospital (CHUV), Lausanne</p>
      <p class="talk-date">May 2021</p>
      <p class="talk-description"></p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Graph Representation Learning & Explainability in Computational Pathology</h3>
      <p class="talk-venue">Swiss Digital Pathology Consortium (SDiPath), Bern</p>
      <p class="talk-date">January 2021</p>
      <p class="talk-description"></p>
    </div>

    <div class="talk-card">
      <span class="talk-type invited">Invited Talk</span>
      <h3 class="talk-title">Deep Learning on Graphs: An Overview</h3>
      <p class="talk-venue">Computer Research Institute of Montreal (CRIM), Montreal</p>
      <p class="talk-date">November 2020</p>
      <p class="talk-description"></p>
    </div>

    <div class="talk-card">
      <span class="talk-type internal">Internal Talks</span>
      <h3 class="talk-title">10+ internal talks at IBM</h3>
      <p class="talk-venue">IBM Research, IBM Watson, IBM Global Business Services</p>
      <p class="talk-date">2019-2021</p>
      <p class="talk-description">Various internal presentations across IBM divisions</p>
    </div>
  </div>
</div>
