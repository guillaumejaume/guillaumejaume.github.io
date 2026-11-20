---
layout: default
title: "Publications"
permalink: /publications/
description: "Peer-reviewed publications and preprints from Guillaume Jaume and the Jaume Lab on AI for pathology, foundation models, multimodal learning and computational oncology."
---

<div class="wrap page">
  <h1 class="page-title">Publications</h1>
  <p class="page-lede">Selected papers from the lab and earlier work. The full list is on <a href="https://scholar.google.com/citations?user=am5XqsQAAAAJ&hl=en">Google Scholar</a>.</p>

  {% assign by_year = site.data.publications | group_by: "year" %}
  {% for group in by_year %}
  <div class="year-group">
  <h2 class="year-heading"><span>{{ group.name }}</span></h2>
  <ul class="pubs">
    {% for p in group.items %}
    <li>
      {% if p.url %}<a class="pub-title" href="{{ p.url }}">{{ p.title }}</a>{% else %}<span class="pub-title">{{ p.title }}</span>{% endif %}
      <div class="pub-authors">{{ p.authors | replace: "; ", ", " | replace: "Guillaume Jaume", "<strong>Guillaume Jaume</strong>" }}</div>
      <div class="pub-venue"><em>{{ p.venue }}</em>{% if p.note %} · <span class="pub-note">{{ p.note }}</span>{% endif %}</div>
      {% if p.url or p.links %}<div class="links pub-links">{% if p.url %}<a href="{{ p.url }}">paper</a>{% endif %}{% for l in p.links %}<a href="{{ l.url }}">{{ l.label }}</a>{% endfor %}</div>{% endif %}
    </li>
    {% endfor %}
  </ul>
  </div>
  {% endfor %}
</div>
