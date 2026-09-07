---
permalink: /projects/
title: "FNR / Industrial Projects"
author_profile: true
---

{% include base_path %}

An overview of the funded research and industrial collaboration projects I contribute to or lead.

<div class="card-grid">
{% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %}
</div>
