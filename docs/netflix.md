---
layout: default
title: "Netflix Meta"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Rough 2020-2025 Netflix animation meta-collection results"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100" alt="Alpha60">
{:/}

<link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
<link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
<script defer type="text/javascript" src="../resources/izzi-table-sort-wcag-22.js"></script>

# Netflix Meta

This is a rough, unvalidated Mellon Method 5 result for the frozen 2020,
2021, 2022, 2023, 2024, and 2025 Alpha60 inventories.

| Cohort | Media objects |
| ---: | ---: |
| 2020 | 1 |
| 2021 | 1 |
| 2022 | 0 |
| 2023 | 1 |
| 2024 | 3 |
| 2025 | 2 |
| **Total** | **8** |

## Weekly graph

Each line is one selected media object. Weekly unique downloader counts are
shown on the 2025 ITU Internet-user scale: raw count multiplied by
<code>ITU users in 2025 / ITU users in the sample-start year</code>.

{::nomarkdown}
{% include mellon-5/runs/2020-2025-itu-2025/netflix-meta-downloads-by-week.svg %}
{:/}

## Aggregate results

{% include mellon-5/runs/2020-2025-itu-2025/netflix-meta-aggregate-table.html %}

These values sum per-object cumulative measurements. They are not
cross-object-deduplicated counts of people or IP addresses.

## Set definition

<pre><code>production_tags contains "netflix animation studios"
OR
(
  distribution_tags contains "netflix"
  AND release.genres intersects {
    "Adult animation", "Animated sitcom"
  }
)</code></pre>

Array matching is exact. The inventory year is the cohort year; release year
does not determine membership.

## Selected media objects

{% include mellon-5/runs/2020-2025-itu-2025/netflix-meta-media-objects-table.html %}

## Data and method

- [Cohorts JSON](../data/mellon-5/runs/2020-2025-itu-2025/netflix-meta-cohorts.json)
- [Weekly CSV](../data/mellon-5/runs/2020-2025-itu-2025/netflix-meta-weekly.csv)
- [Weekly JSON](../data/mellon-5/runs/2020-2025-itu-2025/netflix-meta-weekly.json)
- [Aggregate CSV](../data/mellon-5/runs/2020-2025-itu-2025/netflix-meta-aggregate.csv)
- [Itemized CSV](../data/mellon-5/runs/2020-2025-itu-2025/netflix-meta-itemized.csv)
- [Selection manifest](../data/mellon-5/runs/2020-2025-itu-2025/selection-manifest.json)

Method <code>mellon-5-meta-collection 1.1.0-rough</code>; run
<code>2020-2025-itu-2025</code>; ITU reference year 2025.
