---
layout: default
title: "People"
permalink: /people/
---

<style>
/* FontAwesome CSS for icons (for consistency with other pages) */
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

/* Hero section styling – aligned with Publications/Software pages */
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
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.hero-description {
  font-size: 1.05rem;
  margin: 0 0 20px 0;
  opacity: 0.9;
  max-width: 520px;
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

.hero-social-link .fa-github { color: #333; }
.hero-social-link .fa-graduation-cap { color: #4285f4; }
.hero-social-link .fa-linkedin { color: #0077b5; }
.hero-social-link .fa-x-twitter,
.hero-social-link .x-logo { color: #000; }

.x-logo {
  width: 16px;
  height: 16px;
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

/* People layout */
.page-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 20px;
}

.section-header {
  text-align: center;
  margin-bottom: 40px;
}

.section-header h2 {
  font-size: 2.3rem;
  color: #333;
  margin-bottom: 15px;
  border-bottom: 3px solid #667eea;
  padding-bottom: 10px;
  display: inline-block;
}

.section-header p {
  font-size: 1.05rem;
  color: #555;
  max-width: 700px;
  margin: 0 auto;
}

.people-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 30px;
  margin-top: 20px;
}

.person-card {
  background: white;
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.08);
  border: 1px solid #f0f0f0;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.person-photo {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
  border: 4px solid #e5e7eb;
}

.person-name {
  font-size: 1.3rem;
  font-weight: 700;
  color: #111827;
  margin-bottom: 4px;
}

.person-role {
  font-size: 0.95rem;
  font-weight: 600;
  color: #2563eb;
  margin-bottom: 4px;
}

.person-affiliation {
  font-size: 0.9rem;
  color: #4b5563;
  margin-bottom: 10px;
}

.person-background {
  font-size: 0.9rem;
  color: #6b7280;
  line-height: 1.5;
}

.person-social-links {
  display: flex;
  gap: 10px;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 12px;
}

.person-social-link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 36px;
  height: 36px;
  background: #f3f4f6;
  border-radius: 50%;
  text-decoration: none;
  color: #4b5563;
  border: 1px solid #e5e7eb;
  transition: all 0.2s ease;
}

.person-social-link:hover {
  background: #e5e7eb;
  transform: translateY(-2px);
  color: #111827;
}

.person-social-link i {
  font-size: 1rem;
}

.person-social-link .fa-github { color: #333; }
.person-social-link .fa-graduation-cap { color: #4285f4; }
.person-social-link .fa-linkedin { color: #0077b5; }
.person-social-link .fa-x-twitter { color: #000; }

.person-social-link .x-logo {
  width: 14px;
  height: 14px;
  color: #000;
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

  .people-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero-section">
  <div class="hero-content">
    <div class="hero-text">
      <h1 class="hero-title"><a href="/" style="color: white; text-decoration: none;">Jaume Lab</a></h1>
      <p class="hero-subtitle">AI for Oncologic Pathology. Agentic, multimodal and foundational.</p>
      <div class="hero-buttons">
        <a href="/" class="hero-btn secondary">Home</a>
        <a href="/people/" class="hero-btn primary">People</a>
        <a href="/publications/" class="hero-btn secondary">Publications</a>
        <a href="/software/" class="hero-btn secondary">Software &amp; Datasets</a>
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

<div class="page-content">

  <div class="people-grid">
    <div class="person-card">
      <img src="/assets/people/guillaume.jpeg" alt="Guillaume Jaume" class="person-photo">
      <div class="person-name">Guillaume Jaume</div>
      <div class="person-role">Principal Investigator</div>
      <div class="person-affiliation">Assistant Professor, University of Lausanne (UNIL)</div>
      <div class="person-background">
        MSc from EPFL in EECS, PhD at IBM Research, Postdoc at Harvard Medical School and Mass General Brigham.
      </div>
      <div class="person-social-links">
        <a href="https://github.com/guillaumejaume" target="_blank" rel="noopener" class="person-social-link" aria-label="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://scholar.google.com/citations?user=am5XqsQAAAAJ&hl=en" target="_blank" rel="noopener" class="person-social-link" aria-label="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://www.linkedin.com/in/guillaume-jaume-455169104/" target="_blank" rel="noopener" class="person-social-link" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="https://twitter.com/GuillaumeJaume" target="_blank" rel="noopener" class="person-social-link" aria-label="X"><svg class="x-logo" width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
      </div>
    </div>
 
    <div class="person-card">
      <img src="/assets/people/alex.png" alt="Alexandre de Skowronski" class="person-photo">
      <div class="person-name">Alexandre de Skowronski</div>
      <div class="person-role">Scientist</div>
      <div class="person-background">
        MSc from EPFL in Physics, Software development. 
      </div>
      <div class="person-social-links">
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="GitHub"><i class="fab fa-github"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="X"><svg class="x-logo" width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
      </div>
    </div>

    <div class="person-card">
      <img src="/assets/people/hong.jpeg" alt="Hong Liu" class="person-photo">
      <div class="person-name">Hong Liu</div>
      <div class="person-role">Visiting Researcher</div>
      <div class="person-affiliation">Eindhoven University of Technology</div>
      <div class="person-background">
        Background: to be updated.
      </div>
      <div class="person-social-links">
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="GitHub"><i class="fab fa-github"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="#" target="_blank" rel="noopener" class="person-social-link" aria-label="X"><svg class="x-logo" width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
      </div>
    </div>
  </div>
</div>

