---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The GeoCompute Lab is supported by funding from the National Science Foundation (NSF) and computing resources through NSF ACCESS to advance geospatial research, education, and innovation.

{% include tags.html tags="NSF, NSF ACCESS" %}

{% include search-info.html %}

{% include section.html %}

## Ongoing Projects

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
