---
permalink: /positions/
title: "Open Positions"
modified: 2026-09-07
author_profile: true
---

{% include base_path %}

I am regularly looking for motivated students and researchers to join us, working on trustworthy machine learning, world models, and their application to safety-critical systems, in particular medical imaging and neuro-imaging. Open positions are listed below by type.

## Postdoctoral researcher

No open positions at the moment. Feel free to reach out at salah.ghamizi[at]uni.lu if you are interested in future opportunities.

## PhD student

<div class="card-grid">
{% assign phd_positions = site.positions | where: "category", "phd" %}
{% for post in phd_positions %}
  {% include archive-single-position.html %}
{% endfor %}
</div>

## Internship

<div class="card-grid">
{% assign internship_positions = site.positions | where: "category", "internship" %}
{% for post in internship_positions %}
  {% include archive-single-position.html %}
{% endfor %}
</div>
