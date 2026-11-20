---
layout: default
title: "People"
permalink: /people/
description: "The people of the Jaume Lab at the University of Lausanne: principal investigator, PhD students, research assistants, visiting researchers and alumni working on AI for oncologic pathology."
---

<div class="wrap page">
  <h1 class="page-title">People</h1>
  <p class="page-lede">The lab is based at the Department of Oncology, University of Lausanne. <a href="/#join-us">We are hiring.</a></p>

  <div class="people">
    {% for m in site.data.people.members %}
    <div class="person">
      <img src="{{ m.photo }}" alt="{{ m.name }}" loading="lazy" width="512" height="512">
      <div class="person-name">{{ m.name }}</div>
      <div class="person-role">{{ m.role }}</div>
      {% if m.affiliation %}<div class="person-affil">{{ m.affiliation }}</div>{% endif %}
      {% if m.bio %}<div class="person-bio">{{ m.bio }}</div>{% endif %}
      {% if m.links %}
      <div class="links">{% if m.links.web %}<a href="{{ m.links.web }}">Website</a>{% endif %}{% if m.links.scholar %}<a href="{{ m.links.scholar }}">Scholar</a>{% endif %}{% if m.links.github %}<a href="{{ m.links.github }}">GitHub</a>{% endif %}{% if m.links.linkedin %}<a href="{{ m.links.linkedin }}">LinkedIn</a>{% endif %}{% if m.links.x %}<a href="{{ m.links.x }}">X</a>{% endif %}</div>
      {% endif %}
    </div>
    {% endfor %}
  </div>

  {% if site.data.people.alumni %}
  <section class="section">
    <h2 class="section-title">Alumni</h2>
    <ul class="alumni">
      {% for a in site.data.people.alumni %}<li>{{ a.name }} <span>· {{ a.role }}</span></li>{% endfor %}
    </ul>
  </section>
  {% endif %}
</div>
