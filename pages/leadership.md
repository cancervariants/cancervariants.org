---
layout: page
title: "VICC Leadership"
meta_title: "Leadership"
permalink: '/leadership/'
---

## Co-Directors
{% include member-collection role='co-director' %}

## Project Leaders
{% include member-collection role='project leader' %}

## Former Leadership
### 2020-2021 working groups:
- [Clinical Data Representation](/wg/cdr): 
  - Jeremy Warner
- [In-silico Prediction](/wg/isp): 
  - Ioannis Vlachos
  - Peter Rogan
  - Ian King
- [Knowledge Curation and Interpretation Standards](/wg/kcis): 
  - Dmitriy Sonkin
  - Peter Horak
- [Variant Representation and Search](/wg/vrs): 
  - Shirley Li

### Founders and leadership up to 2020:
{% assign inactive_leaders = site.leadership | where:"status","inactive" | map: "name" %}
{{ inactive_leaders | join: ", " }}