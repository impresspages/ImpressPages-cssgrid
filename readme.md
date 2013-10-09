# ImpressPages Grid

Responsive dynamic grid for web.

## Features

ImpressPages grid is 12 column layout grid. Three sizes for mobile, medium (480px) and large (980px) screens provided.
This grid follows "mobile first" concept.

## Usage

Add the link to grid.css in your HTML file. For example,
...
<link rel="stylesheet" href="grid.css" />
...

The example below shows the sample usage of the grid. For mobile devices, the content is displayed in full width (12
columns). For large and medium screens, the content is shown in two columns of different width (8 + 4 columns for medium
screens, 9 + 3 columns for large screens):
...    
        <div class="col_12 col_md_8 col_lg_9">
            SAMPLE CONTENT LEFT
        </div>
        <div class="col_12 col_md_4 col_lg_3">
            SAMPLE CONTENT RIGHT
        </div>
...

This grid also has been provided in LESS CSS format.

## Requirements

Requires CSS3.


