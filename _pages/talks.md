---
layout: default
title: "Communication"
permalink: /talks/
---
<style>
.page-content {
  max-width: 1300px;
  margin: 0 auto;
  padding: 40px 20px;
}

.talks-table-wrap {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
  border: 1px solid #f0f0f0;
  overflow: hidden;
}

.talks-table-scroll {
  overflow-x: auto;
}

.talks-table {
  width: 100%;
  border-collapse: collapse;
  min-width: 820px;
}

.talks-table thead th {
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

.talks-table tbody tr {
  border-bottom: 1px solid #eef1f5;
}

.talks-table tbody tr:nth-child(even) {
  background: #fbfcfe;
}

.talks-table tbody tr:hover {
  background: #f3f7ff;
}

.talks-table td {
  vertical-align: top;
  padding: 14px 16px;
  color: #374151;
  font-size: 0.95rem;
  line-height: 1.45;
}

.talk-date {
  white-space: nowrap;
  font-weight: 600;
  color: #4b5563;
}

.talk-title-cell {
  font-weight: 600;
  color: #111827;
  max-width: 460px;
  line-height: 1.4;
}

.talk-venue-cell {
  color: #4b5563;
  font-weight: 500;
  max-width: 320px;
}

.talk-location-cell {
  color: #6b7280;
  max-width: 240px;
}

/* Dates use: DD Mon YYYY when exact day is known, otherwise Mon YYYY. */
@media (max-width: 768px) {
  .page-content {
    padding: 24px 12px;
  }

  .talks-table {
    min-width: unset;
    border-collapse: separate;
  }

  .talks-table thead {
    display: none;
  }

  .talks-table tbody tr {
    display: block;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    margin: 0 0 10px 0;
    padding: 8px 0;
    background: white;
  }

  .talks-table tbody tr:nth-child(even) {
    background: white;
  }

  .talks-table td {
    display: block;
    border: none;
    padding: 6px 12px;
  }

  .talks-table td::before {
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
  <div class="talks-table-wrap">
    <div class="talks-table-scroll">
      <table class="talks-table">
        <thead>
          <tr>
            <th>Date</th>
            <th>Title</th>
            <th>Venue</th>
            <th>Location</th>
          </tr>
        </thead>
        <tbody>
          <tr><td data-label="Date" class="talk-date">19 Nov 2026</td><td data-label="Title" class="talk-title-cell">New Directions in AI for Pathology &amp; Oncology</td><td data-label="Venue" class="talk-venue-cell">CompBio Seminar</td><td data-label="Location" class="talk-location-cell">🇨🇭 Lausanne, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">18 Nov 2026</td><td data-label="Title" class="talk-title-cell">AI Agents in Pathology</td><td data-label="Venue" class="talk-venue-cell">ESMO AI</td><td data-label="Location" class="talk-location-cell">🇩🇪 Berlin, Germany</td></tr>
          <tr><td data-label="Date" class="talk-date">19 Jun 2026</td><td data-label="Title" class="talk-title-cell">Agentic AI in Pathology</td><td data-label="Venue" class="talk-venue-cell">European Conference on Digital Pathology</td><td data-label="Location" class="talk-location-cell">🇦🇹 Graz, Austria</td></tr>
          <tr><td data-label="Date" class="talk-date">08 Jun 2026</td><td data-label="Title" class="talk-title-cell">Multimodal Foundation Modeling in Pathology</td><td data-label="Venue" class="talk-venue-cell">AI x Bio Conference</td><td data-label="Location" class="talk-location-cell">🇬🇧 Cambridge, UK</td></tr>
          <tr><td data-label="Date" class="talk-date">21 May 2026</td><td data-label="Title" class="talk-title-cell">AI Foundation Modeling for Oncologic Pathology</td><td data-label="Venue" class="talk-venue-cell">LBiBER Seminar Series</td><td data-label="Location" class="talk-location-cell">🇨🇭 Basel, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">07 May 2026</td><td data-label="Title" class="talk-title-cell">Towards Robust AI Models in Pathology</td><td data-label="Venue" class="talk-venue-cell">ESAC Meeting</td><td data-label="Location" class="talk-location-cell">🇮🇹 Milan, Italy</td></tr>
          <tr><td data-label="Date" class="talk-date">06 May 2026</td><td data-label="Title" class="talk-title-cell">Open-ended AI Modeling in Histology</td><td data-label="Venue" class="talk-venue-cell">Symposium on AI for Clinical and Translational Medicine</td><td data-label="Location" class="talk-location-cell">🇨🇭 Lausanne, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">17 Mar 2026</td><td data-label="Title" class="talk-title-cell">AI Foundational Modeling in Pathology</td><td data-label="Venue" class="talk-venue-cell">CompBio Meeting, EPFL</td><td data-label="Location" class="talk-location-cell">🇨🇭 Lausanne, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">26 Feb 2026</td><td data-label="Title" class="talk-title-cell">An Introduction to AI in Pathology</td><td data-label="Venue" class="talk-venue-cell">Computational Pathology School, MedUni Vienna</td><td data-label="Location" class="talk-location-cell">🇦🇹 Vienna, Austria</td></tr>
          <tr><td data-label="Date" class="talk-date">05 Nov 2026</td><td data-label="Title" class="talk-title-cell">Towards Generalist AI Models in Pathology</td><td data-label="Venue" class="talk-venue-cell">SKKU Seminar</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">May 2025</td><td data-label="Title" class="talk-title-cell">Toward Generalist AI Models in Pathology</td><td data-label="Venue" class="talk-venue-cell">AbbVie</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Apr 2025</td><td data-label="Title" class="talk-title-cell">Toward Generalist AI Models in Pathology</td><td data-label="Venue" class="talk-venue-cell">Microsoft Research</td><td data-label="Location" class="talk-location-cell">🇺🇸 Boston, USA</td></tr>
          <tr><td data-label="Date" class="talk-date">Mar 2025</td><td data-label="Title" class="talk-title-cell">Advancing Translational Research with AI in Oncologic Pathology</td><td data-label="Venue" class="talk-venue-cell">CRUK, University of Cambridge</td><td data-label="Location" class="talk-location-cell">🇬🇧 Cambridge, UK</td></tr>
          <tr><td data-label="Date" class="talk-date">Mar 2025</td><td data-label="Title" class="talk-title-cell">AI for Computational Toxicologic Pathology</td><td data-label="Venue" class="talk-venue-cell">Novartis</td><td data-label="Location" class="talk-location-cell">🇺🇸 Boston, USA</td></tr>
          <tr><td data-label="Date" class="talk-date">Mar 2025</td><td data-label="Title" class="talk-title-cell">Bringing Spatial Transcriptomics into The World of Deep Learning</td><td data-label="Venue" class="talk-venue-cell">University of Sydney</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Dec 2024</td><td data-label="Title" class="talk-title-cell">Scaling Spatial Transcriptomics and Histology with HEST</td><td data-label="Venue" class="talk-venue-cell">Owkin</td><td data-label="Location" class="talk-location-cell">🇫🇷 Paris, France</td></tr>
          <tr><td data-label="Date" class="talk-date">Nov 2024</td><td data-label="Title" class="talk-title-cell">AI for Preclinical Drug Safety Assessment</td><td data-label="Venue" class="talk-venue-cell">Roche</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Sep 2024</td><td data-label="Title" class="talk-title-cell">Multimodal Representation Learning in AI for Pathology</td><td data-label="Venue" class="talk-venue-cell">Lunit</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">May 2024</td><td data-label="Title" class="talk-title-cell">3D Computational Pathology: Towards Enhanced Patient Prognostication</td><td data-label="Venue" class="talk-venue-cell">UniBe</td><td data-label="Location" class="talk-location-cell">🇨🇭 Bern, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">May 2024</td><td data-label="Title" class="talk-title-cell">Towards General-Purpose AI Models for Histology</td><td data-label="Venue" class="talk-venue-cell">CHUV</td><td data-label="Location" class="talk-location-cell">🇨🇭 Lausanne, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">Jul 2023</td><td data-label="Title" class="talk-title-cell">Deep Learning for Pathology Image Analysis</td><td data-label="Venue" class="talk-venue-cell">PariSanté Campus</td><td data-label="Location" class="talk-location-cell">🇫🇷 Paris, France</td></tr>
          <tr><td data-label="Date" class="talk-date">Jul 2023</td><td data-label="Title" class="talk-title-cell">Latest trends in Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">University of Bern</td><td data-label="Location" class="talk-location-cell">🇨🇭 Bern, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">Nov 2022</td><td data-label="Title" class="talk-title-cell">A Tour of Computational Pathology: Methods and Applications</td><td data-label="Venue" class="talk-venue-cell">UC Berkeley</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Sep 2022</td><td data-label="Title" class="talk-title-cell">Interpretable Deep Learning in Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">Dana-Farber Cancer Institute</td><td data-label="Location" class="talk-location-cell">🇺🇸 Boston, USA</td></tr>
          <tr><td data-label="Date" class="talk-date">Feb 2022</td><td data-label="Title" class="talk-title-cell">Graph Representation Learning in Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">Symposium on DigPath in the DACH Region</td><td data-label="Location" class="talk-location-cell">🇨🇭 Bern, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">Oct 2021</td><td data-label="Title" class="talk-title-cell">HistoCartography: Graph representations and models in Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">Tissue Image Analytics Centre</td><td data-label="Location" class="talk-location-cell">🇬🇧 Warwick, UK</td></tr>
          <tr><td data-label="Date" class="talk-date">Oct 2021</td><td data-label="Title" class="talk-title-cell">Graph Representations and Models in Digital Pathology</td><td data-label="Venue" class="talk-venue-cell">Charité University Hospital</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Jul 2021</td><td data-label="Title" class="talk-title-cell">Weakly-Supervised Learning for Whole-Slide-Image Segmentation</td><td data-label="Venue" class="talk-venue-cell">PathAI</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Jul 2021</td><td data-label="Title" class="talk-title-cell">A Graph Network Tour of Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">Harvard Medical School</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">May 2021</td><td data-label="Title" class="talk-title-cell">Computational Pathology: Building Interpretable AI at Scale</td><td data-label="Venue" class="talk-venue-cell">Lausanne University Hospital (CHUV)</td><td data-label="Location" class="talk-location-cell">🇨🇭 Lausanne, Switzerland</td></tr>
          <tr><td data-label="Date" class="talk-date">Jan 2021</td><td data-label="Title" class="talk-title-cell">Graph Representation Learning &amp; Explainability in Computational Pathology</td><td data-label="Venue" class="talk-venue-cell">Swiss Digital Pathology Consortium (SDiPath)</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
          <tr><td data-label="Date" class="talk-date">Nov 2020</td><td data-label="Title" class="talk-title-cell">Deep Learning on Graphs: An Overview</td><td data-label="Venue" class="talk-venue-cell">Computer Research Institute of Montreal (CRIM)</td><td data-label="Location" class="talk-location-cell">💻 Virtual</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
