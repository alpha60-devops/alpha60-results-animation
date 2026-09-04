---
layout: default
title: "Superhero Animation"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Rough 2020-2025 superhero-animation meta-collection results"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100" alt="Alpha60">
{:/}

<link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
<link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
<script defer type="text/javascript" src="../resources/izzi-table-sort-wcag-22.js"></script>
<script defer type="text/javascript" src="../resources/izzi-graph-hover-txt-polyline-red.js"></script>

# Superhero Animation

This is a rough, unvalidated Mellon Method 5 result for the frozen 2020,
2021, 2022, 2023, 2024, and 2025 Alpha60 inventories.

| Cohort | Media objects |
| ---: | ---: |
| 2020 | 0 |
| 2021 | 2 |
| 2022 | 2 |
| 2023 | 2 |
| 2024 | 2 |
| 2025 | 3 |
| **Total** | **11** |

## Weekly graph

Each line is one selected media object. Weekly unique downloader counts are
shown on the 2025 ITU Internet-user scale: raw count multiplied by
<code>ITU users in 2025 / ITU users in the sample-start year</code>.

{::nomarkdown}
{% include mellon-5/runs/2020-2025-itu-2025/superhero-animation-downloads-by-week.svg %}
{:/}

## Aggregate results

{% include mellon-5/runs/2020-2025-itu-2025/superhero-animation-aggregate-table.html %}

These values sum per-object cumulative measurements. They are not
cross-object-deduplicated counts of people or IP addresses.

## Set definition

<pre><code>collection_tags contains "animation"
AND
(
  release.genres contains "Superhero"
  OR collection_tags contains "spider_man"
)</code></pre>

All reviewed Spider-Man media objects carry <code>spider_man</code>; there is
no runtime title substring match. Array matching is exact, and the inventory
year is the cohort year.

## Selected media objects

{% include mellon-5/runs/2020-2025-itu-2025/superhero-animation-media-objects-table.html %}

## Data and method

- [Cohorts JSON](../data/mellon-5/runs/2020-2025-itu-2025/superhero-animation-cohorts.json)
- [Weekly CSV](../data/mellon-5/runs/2020-2025-itu-2025/superhero-animation-weekly.csv)
- [Weekly JSON](../data/mellon-5/runs/2020-2025-itu-2025/superhero-animation-weekly.json)
- [Aggregate CSV](../data/mellon-5/runs/2020-2025-itu-2025/superhero-animation-aggregate.csv)
- [Itemized CSV](../data/mellon-5/runs/2020-2025-itu-2025/superhero-animation-itemized.csv)
- [Selection manifest](../data/mellon-5/runs/2020-2025-itu-2025/selection-manifest.json)

Method <code>mellon-5-meta-collection 1.1.0-rough</code>; run
<code>2020-2025-itu-2025</code>; ITU reference year 2025.
