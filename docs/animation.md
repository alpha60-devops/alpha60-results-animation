---
layout: default
---
<script src="https://unpkg.com/tabular/dist/tabular.min.js"></script>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    // Select all table elements on the page
    const tables = document.querySelectorAll('table');

    // Apply Tabular to each table found
    tables.forEach(table => {
      // Basic initialization for sortable tables.
      // You might need to adjust options based on your table structure (e.g., header rows).
      new Tabular(table, {
        // 'dataTabular' makes the table sortable by clicking on headers.
        // It assumes the first row (<tr>) contains the header cells (<th>).
        dataTabular: true
      });
    });
  });
</script>


{::nomarkdown}
<img src="../image/a60-logo-block-gray.simple.svg?sanitize=true" height="50" width="100">
{:/}

<div style="height: 50px;"></div>


# Animation

## Results
<div style="height: 50px;"></div>

### Tables

{% include animation-meta-collection-table.html %}
<div style="height: 50px;"></div>

{% include animation-media-objects-table.html %}
<div style="height: 50px;"></div>


### Graphs

{::nomarkdown}
{% include animation-downloads-by-week-cumulative-normalized-start.svg %}
{:/}

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../resources/izzi-script-graph-hover-txt-polyline.js">
</script>
<div style="height: 50px;"></div>



## Commentary, Questions

### Global Media by Week


<div style="height: 50px;"></div>

{::nomarkdown}
<svg width="100" height=100>
    <circle cx="20" cy="50" r="10" fill="black"/>
</svg>
{:/}
