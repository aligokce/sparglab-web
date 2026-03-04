---
title: Projects
nav:
  order: 3
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="software, dataset, research-grant" %}

{% include search-info.html %}

{% include section.html %}

## Ongoing

{% include list.html component="card" data="projects" filter="group == 'ongoing'" %}

{% include section.html %}

## Past

{% include list.html component="card" data="projects" filter="!group" %}
