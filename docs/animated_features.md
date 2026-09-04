---
layout: default
title: "Animated Features"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Rough 2020-2025 animated-feature meta-collection results"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100" alt="Alpha60">
{:/}

<link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
<link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
<script defer type="text/javascript" src="../resources/izzi-table-sort-wcag-22.js"></script>

# Animated Features

This is a rough, unvalidated Mellon Method 5 result for the frozen 2020,
2021, 2022, 2023, 2024, and 2025 Alpha60 inventories.

## Set definition

<pre><code>collection_tags contains "animation"
AND media_object.type == "film"</code></pre>

The <code>animation</code> tag comes from the hand-selected Animation
publication list. Array matching is exact, and the inventory year is the
cohort year.

| Cohort | Media objects |
| ---: | ---: |
| 2020 | 3 |
| 2021 | 4 |
| 2022 | 1 |
| 2023 | 2 |
| 2024 | 3 |
| 2025 | 2 |
| **Total** | **15** |

## Weekly graph

Each line is one selected media object. Weekly unique downloader counts are
shown on the 2025 ITU Internet-user scale: raw count multiplied by
<code>ITU users in 2025 / ITU users in the sample-start year</code>.

{::nomarkdown}
{% include mellon-5/runs/2020-2025-itu-2025/animated-features-downloads-by-week.svg %}
{:/}

## Aggregate results

{% include mellon-5/runs/2020-2025-itu-2025/animated-features-aggregate-table.html %}

These values sum per-object cumulative measurements. They are not
cross-object-deduplicated counts of people or IP addresses.

## Selected media objects

{% include mellon-5/runs/2020-2025-itu-2025/animated-features-media-objects-table.html %}

## Data and method

- [Cohorts JSON](../data/mellon-5/runs/2020-2025-itu-2025/animated-features-cohorts.json)
- [Weekly CSV](../data/mellon-5/runs/2020-2025-itu-2025/animated-features-weekly.csv)
- [Weekly JSON](../data/mellon-5/runs/2020-2025-itu-2025/animated-features-weekly.json)
- [Aggregate CSV](../data/mellon-5/runs/2020-2025-itu-2025/animated-features-aggregate.csv)
- [Itemized CSV](../data/mellon-5/runs/2020-2025-itu-2025/animated-features-itemized.csv)
- [Selection manifest](../data/mellon-5/runs/2020-2025-itu-2025/selection-manifest.json)

Method <code>mellon-5-meta-collection 1.1.0-rough</code>; run
<code>2020-2025-itu-2025</code>; ITU reference year 2025.
