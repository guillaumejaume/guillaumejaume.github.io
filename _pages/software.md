---
layout: default
title: "Software & Datasets"
permalink: /software/
description: "Open-source software, models and datasets released by Guillaume Jaume and the Jaume Lab for computational pathology research."
---

<div class="wrap page">
  <h1 class="page-title">Software &amp; Datasets</h1>
  <p class="page-lede">Open-source libraries, benchmarks and datasets we have built. More on <a href="https://github.com/guillaumejaume">GitHub</a> and <a href="https://huggingface.co/MahmoodLab">Hugging Face</a>.</p>

  <ul class="tools">
    {% for t in site.data.software %}
    <li>
      <div><span class="tool-name">{{ t.name }}</span><span class="tool-kind">{{ t.kind }}</span></div>
      <div>
        <p class="tool-text">{{ t.text }}</p>
        <div class="links">{% for l in t.links %}<a href="{{ l.url }}">{{ l.label }}</a>{% endfor %}</div>
      </div>
    </li>
    {% endfor %}
  </ul>
</div>
