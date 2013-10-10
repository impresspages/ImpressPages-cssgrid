# ImpressPages Grid

Responsive dynamic grid for web.

## Features

ImpressPages grid is 12 column layout grid. Three sizes for mobile, medium (480px) and large (980px) screens provided.
This grid follows *mobile first* concept.

This grid also has been provided in LESS CSS format.

## Usage

Add the link to grid.css in your HTML file. For example,

    <link rel="stylesheet" href="grid.css" />

Create a `div` element and add the column class provided in the `grid.css` file. 

Use no prefix for layouts available for all devices (i.e., `col_1`).
Add _md_ prefix for medium size screens (i.e., `col_md_1`).
Add _lg_ prefix for large size screens (i.e., `col_lg_1`).

To be exact, the grid class uses the following syntax:

    col_[|md_|lg_]{1..12}

The sum of all columns should be equal to 12.

The example below shows the sample usage of the grid. For mobile devices, the content is displayed in full width (12
columns). For large and medium screens, the content is shown in two columns of different width (8 + 4 columns for medium
screens, 9 + 3 columns for large screens):

    <div class="col_12 col_md_8 col_lg_9">
        SAMPLE CONTENT LEFT
    </div>
    <div class="col_12 col_md_4 col_lg_3">
        SAMPLE CONTENT RIGHT
    </div>

If you need to preview the grid layout, add the `showGridHint` class to a container element, and add the `gridHint` class
to a row.

## Requirements

Requires CSS3.


