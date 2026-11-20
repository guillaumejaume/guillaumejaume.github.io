---
layout: default
title: "Talks"
permalink: /talks/
description: "Invited talks, lectures and conference presentations by Guillaume Jaume on AI for pathology, foundation models and agentic AI in oncology."
---

<div class="wrap page">
  <h1 class="page-title">Talks</h1>
  <p class="page-lede">Invited talks, lectures and conference presentations.</p>

  {% assign now = site.time | date: "%s" | plus: 0 %}
  {% assign upcoming = "" | split: "" %}
  {% assign past = "" | split: "" %}
  {% for t in site.data.talks %}
    {% assign ts = t.date | date: "%s" | plus: 0 %}
    {% if ts >= now %}{% assign upcoming = upcoming | push: t %}{% else %}{% assign past = past | push: t %}{% endif %}
  {% endfor %}

  {% if upcoming.size > 0 %}
  <section class="section">
    <h2 class="section-title">Upcoming</h2>
    <ul class="talks">
      {% assign upcoming = upcoming | reverse %}
      {% for t in upcoming %}{% include talk-item.html t=t %}{% endfor %}
    </ul>
  </section>
  {% endif %}

  <section class="section">
    <h2 class="section-title">Past</h2>
    <ul class="talks">
      {% for t in past %}{% include talk-item.html t=t %}{% endfor %}
    </ul>
  </section>
</div>
