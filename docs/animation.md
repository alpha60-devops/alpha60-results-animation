---
layout: default
title: "Animation"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Analysis of Animation-genre peer-to-peer distribution"
---

{::nomarkdown}
<img src="../resources/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100">
{:/}

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
	src="../resources/izzi-map-leaflet-geojson-v7.6.js">
</script>

<!-- Preload the CSS without blocking rendering -->
<link rel="preload" href="../resources/izzi-table-wcag-22.css" as="style" onload="this.onload=null;this.rel='stylesheet'">

<!-- Fallback for users who have JavaScript disabled -->
<noscript>
  <link rel="stylesheet" href="../resources/izzi-table-wcag-22.css">
</noscript>

<div style="height: 50px;"></div>


# Animation
<div style="height: 50px;"></div>


## Graphs

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

{::nomarkdown}
{% include animation-downloads-by-week-normalized-start.svg %}
{:/}
<div style="height: 25px;"></div>

{% include animation-graph-table.html %}
<div style="height: 50px;"></div>


## Maps

{% include animation-spatial-carto-table.html %}
<div style="height: 50px;"></div>


## Tables

<script defer type="text/javascript" crossorigin="anonymous" id="table-sort"
	src="../resources/izzi-table-sort-wcag-22.js">
</script>

<!-- Preload the CSS without blocking rendering -->
<link rel="preload" href="../resources/izzi-table-sort-wcag-22.css" as="style" onload="this.onload=null;this.rel='stylesheet'">

<!-- Fallback for users who have JavaScript disabled -->
<noscript>
  <link rel="stylesheet" href="../resources/izzi-table-sort-wcag-22.css">
</noscript>


{% include animation-meta-collection-table.html %}
<div style="height: 50px;"></div>

{% include animation-media-objects-table.html %}
<div style="height: 50px;"></div>

{% include animation-geo-slices-usa-weeks-1-5-15.html %}
<div style="height: 50px;"></div>

{% include animation-geo-slices-africa.html %}
<div style="height: 50px;"></div>

{% include animation-geo-slices-asia.html %}
<div style="height: 50px;"></div>


## Commentary, Questions


{::nomarkdown}
<svg width="100" height=100>
	<circle cx="20" cy="50" r="10" fill="black"/>
</svg>
{:/}
