---
layout: page
title: "VICC Leadership"
meta_title: "Leadership"
permalink: '/leadership/'
---

## Co-Directors
{% include member-collection role='co-director' %}

## Working group leaders
{% include member-collection role='working group leader' %}

## Project Leaders
{% include member-collection role='project leader' %}

## Former Leadership
{% assign inactive_leaders = site.leadership | where:"status","inactive" | map: "name" %}
{{ inactive_leaders | join: ", " }}