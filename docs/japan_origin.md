---
layout: default
title: "Japan-Origin Animation"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Rough 2020-2025 Japan-origin animation meta-collection results"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100" alt="Alpha60">
{:/}

<link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
<link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
<script defer type="text/javascript" src="../resources/izzi-table-sort-wcag-22.js"></script>

# Japan-Origin Animation

This is a rough, unvalidated Mellon Method 5 result for the frozen 2020,
2021, 2022, 2023, 2024, and 2025 Alpha60 inventories.

| Cohort | Media objects |
| ---: | ---: |
| 2020 | 3 |
| 2021 | 6 |
| 2022 | 0 |
| 2023 | 0 |
| 2024 | 1 |
| 2025 | 4 |
| **Total** | **14** |

## Weekly graph

Each line is one selected media object. Weekly unique downloader counts are
shown on the 2025 ITU Internet-user scale: raw count multiplied by
<code>ITU users in 2025 / ITU users in the sample-start year</code>.

{::nomarkdown}
{% include mellon-5/runs/2020-2025-itu-2025/japan-origin-downloads-by-week.svg %}
{:/}

## Aggregate results

{% include mellon-5/runs/2020-2025-itu-2025/japan-origin-aggregate-table.html %}

These values sum per-object cumulative measurements. They are not
cross-object-deduplicated counts of people or IP addresses.

## Set definition

<pre><code>collection_tags contains "animation"
AND
(
  release.countries_of_origin contains "Japan"
  OR release.original_languages contains "Japanese"
  OR collection_tags contains "japan_origin"
)</code></pre>

Array matching is exact. The inventory year is the cohort year; release year
does not determine membership. Demon Slayer is deferred until a future 2020
cohort and is not listed, graphed, or counted in this run.

## Selected media objects

{% include mellon-5/runs/2020-2025-itu-2025/japan-origin-media-objects-table.html %}

## Data and method

- [Cohorts JSON](../data/mellon-5/runs/2020-2025-itu-2025/japan-origin-cohorts.json)
- [Weekly CSV](../data/mellon-5/runs/2020-2025-itu-2025/japan-origin-weekly.csv)
- [Weekly JSON](../data/mellon-5/runs/2020-2025-itu-2025/japan-origin-weekly.json)
- [Aggregate CSV](../data/mellon-5/runs/2020-2025-itu-2025/japan-origin-aggregate.csv)
- [Itemized CSV](../data/mellon-5/runs/2020-2025-itu-2025/japan-origin-itemized.csv)
- [Selection manifest](../data/mellon-5/runs/2020-2025-itu-2025/selection-manifest.json)

Method <code>mellon-5-meta-collection 1.1.0-rough</code>; run
<code>2020-2025-itu-2025</code>; ITU reference year 2025.
