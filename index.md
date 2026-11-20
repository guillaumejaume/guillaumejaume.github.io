---
layout: default
title: "Jaume Lab"
full_title: "Jaume Lab | AI for Oncologic Pathology, UNIL"
news_visible: 8
---

<div class="wrap page home">
  <div>
    <section class="intro">
      <p>The Jaume Lab develops AI methods for pathology and oncology. We started in February 2026 at the <a href="https://www.unil.ch/dof/en/home.html">Department of Oncology</a> of the University of Lausanne (UNIL).</p>
      <p>We build models that read tissue alongside molecular and clinical data, and use them to find biomarkers and support diagnosis. We release our code, models and datasets openly.</p>
    </section>

    <section class="section">
      <h2 class="section-title">Research</h2>
      <ul class="themes">
        <li>
          <strong>Agentic AI for pathology</strong>
          <span>Systems that plan and carry out multi-step analyses of whole-slide images, much like a pathologist working through a case.</span>
        </li>
        <li>
          <strong>Biomarker discovery</strong>
          <span>Linking tissue morphology to molecular profiles and patient outcomes to find markers that guide treatment.</span>
        </li>
        <li>
          <strong>Multimodal foundation models</strong>
          <span>Models trained jointly on histology, spatial omics, text and clinical records, released as tools others can build on.</span>
        </li>
      </ul>
      <p class="contact-line" style="margin-top: 16px;">We collaborate closely with Harvard Medical School, Mass General Brigham, EPFL and ETH Zurich.</p>
    </section>

    <section class="section">
      <h2 class="section-title" id="join-us">Join us</h2>
      <p>We are looking for PhD students, postdocs and interns who want to work on AI with direct applications in cancer research and care. Students with a background in computer science, engineering, physics or computational biology are welcome to apply.</p>
      <p><a href="https://docs.google.com/forms/d/e/1FAIpQLSfK4Qee0M5HJj7MFDoH3pcjU27s-Uf4DO3MgYVFZhUyBmu_LA/viewform">Apply through this form</a>, or write to <a href="mailto:guillaume.jaume@unil.ch">guillaume.jaume@unil.ch</a>.</p>
    </section>
  </div>

  <aside>
    <h2 class="section-title">News</h2>
    {% assign n = page.news_visible %}
    <ul class="news-list">
      {% for item in site.data.news limit: n %}{% include news-item.html item=item %}{% endfor %}
    </ul>
    {% if site.data.news.size > n %}
    <details class="news-more">
      <summary>Earlier news</summary>
      <ul class="news-list">
        {% for item in site.data.news offset: n %}{% include news-item.html item=item %}{% endfor %}
      </ul>
    </details>
    {% endif %}
  </aside>
</div>
