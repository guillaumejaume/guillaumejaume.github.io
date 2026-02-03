---
layout: default
title: "Communication"
permalink: /talks/
---

<style>
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

@media (max-width: 768px) {
  .talks-grid {
    grid-template-columns: 1fr;
  }
}
</style>

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
