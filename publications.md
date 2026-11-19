---
layout: default
title: Publications
permalink: /publications/
redirect_from:
  - /publication/2024-03-11-undersmoothing
  - /publication/2024-03-15-robustness-structure-learning
  - /publication/2025-11-19-asilomar
  - /publication/2025-12-07-dots
---

# Publications

<p class="muted">See also <a href="https://scholar.google.com/citations?user=q3_gY8MAAAAJ">Google Scholar</a>.</p>

{% assign by_year = site.data.publications | group_by: "year" %}
{% for group in by_year %}
<h2 class="year">{{ group.name }}</h2>
<ol class="pubs">
  {%- for pub in group.items %}
  {% include publication.html pub=pub %}
  {%- endfor %}
</ol>
{% endfor %}
