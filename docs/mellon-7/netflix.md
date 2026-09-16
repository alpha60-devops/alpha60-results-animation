---
layout: default
title: "Netflix — Mellon 7 draft"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Draft 2017–2026 Netflix peer-swarm analysis"
---

{::nomarkdown}
<img src="../../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100" alt="Alpha60">
{:/}

<link rel="stylesheet" href="../../resources/izzi-table-wcag-22.css">
<script defer type="text/javascript" crossorigin="anonymous" id="table-sort"
  src="../../resources/izzi-table-sort-wcag-22.js"></script>
<link rel="preload" href="../../resources/izzi-table-sort-wcag-22.css" as="style"
  onload="this.onload=null;this.rel='stylesheet'">
<noscript>
  <link rel="stylesheet" href="../../resources/izzi-table-sort-wcag-22.css">
</noscript>
<style>
  .table-container { overflow-x: auto; }
  table.mellon-table thead th {
    font-family: inherit;
    font-size: 12px;
    line-height: 1.25;
  }
  table.mellon-table thead th button {
    color: inherit;
    font: inherit;
    font-weight: inherit;
  }
  table.mellon-table .column-primary,
  table.mellon-table tbody th[scope="row"] {
    min-width: 30em;
    white-space: nowrap;
  }
  table.mellon-table .column-compact {
    min-width: 4.5em;
    width: 4.5em !important;
  }
</style>
<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
  src="../../resources/izzi-graph-hover-txt-polyline-red.js"></script>

# Netflix

> **Draft publication.** This Mellon 7 output is available for review but does
> not replace the stable Mellon 7 pages. All H-08 Animation dispositions
> are complete. The 2026 normalization uses the
> unapproved provisional 6.1-billion Internet-user value and must not be read
> as final.

## Set definition

reviewed Animation universe AND exact Netflix distribution evidence.

This set uses the frozen 65-member Animation predecessor slice plus 21 owner-approved additions: `invincible-401`, `demon-slayer-kimetsu-no-yaiba-the-movie-infinity-castle`, `toy-story-5`, `all-you-need-is-kill`, `goat-2026`, `hoppers`, `super-mario-galaxy-movie`, `long-story-short-01`, `mating-season-01`, `stranger-things-tales-from-85-01`, `legend-of-galactic-heroes-die-neue-these`, `lego-star-wars-holiday-special-2020`, `archer-1408`, `dang-01`, `ghost-in-the-shell-2026-01`, `legend-of-aang-the-last-airbender`, `legend-of-vox-machina-410`, `president-curtis-01`, `rick-and-morty-901`, `star-wars-visions-the-ninth-jedi-01`, and `x-men-97-201`.

All matching uses exact canonical values. The Animation-universe requirement
is applied before every category predicate.

The cohort year comes from each frozen annual inventory, not release year.
Category memberships are non-exclusive. Platform evidence does not establish
current availability, exclusivity, territory, or availability window.

| Cohort | Media objects |
| ---: | ---: |
| 2017 | 0 |
| 2018 | 0 |
| 2019 | 2 |
| 2020 | 3 |
| 2021 | 5 |
| 2022 | 0 |
| 2023 | 1 |
| 2024 | 3 |
| 2025 | 2 |
| 2026 | 4 |
| **Total** | **20** |

<div style="height: 50px;"></div>

## Graphs

Each line is one selected media object. Weekly unique downloader counts are
shown on the 2025 ITU Internet-user scale; 2026 is provisional as noted above.

{::nomarkdown}
{% include mellon-7/runs/2017-2026-itu-2025/netflix-downloads-by-week.svg %}
{:/}


<div style="height: 50px;"></div>

## Tables

{% include mellon-7/runs/2017-2026-itu-2025/netflix-aggregate-table.html %}
<div style="height: 50px;"></div>

{% include mellon-7/runs/2017-2026-itu-2025/netflix-media-objects-table.html %}
<div style="height: 50px;"></div>

{% include mellon-7/runs/2017-2026-itu-2025/netflix-geo-slices-usa-weeks-1-5-15.html %}
<div style="height: 50px;"></div>

{% include mellon-7/runs/2017-2026-itu-2025/netflix-geo-slices-africa.html %}
<div style="height: 50px;"></div>

{% include mellon-7/runs/2017-2026-itu-2025/netflix-geo-slices-asia.html %}

<div style="height: 50px;"></div>


## Data and method

- [Cohorts JSON](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-cohorts.json)
- [Weekly CSV](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-weekly.csv)
- [Weekly JSON](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-weekly.json)
- [Itemized CSV](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-itemized.csv)
- [Itemized JSON](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-itemized.json)
- [Exclusions CSV](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-exclusions.csv)
- [Exclusions JSON](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-exclusions.json)
- [Geographic slices CSV](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-geo-slices.csv)
- [Geographic slices JSON](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-geo-slices.json)
- [Table manifest](../../data/mellon-7/runs/2017-2026-itu-2025/netflix-table-manifest.json)
- [Selection manifest](../../data/mellon-7/runs/2017-2026-itu-2025/selection-manifest.json)
- [Build receipt](../../data/mellon-7/runs/2017-2026-itu-2025/build-receipt.json)
- [Independent validation](../../data/mellon-7/runs/2017-2026-itu-2025/independent-validation-receipt.json)

Method `mellon-7-animation 1.0.0`; run `2017-2026-itu-2025`;
canonical metadata `09eab5dec98a230791a44333017907f0e0348ac9`; ITU reference year 2025.
