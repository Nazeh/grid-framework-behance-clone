# Grid framework Behance clone

A clone of [Behance.net](https://www.behance.net/) website page, as a demonstration of a custom grid based CSS framework.<br>
<br>
Built With:
* HTML5
* CSS3
* Sass

# GitHub Page
[Live version](https://raw.githack.com/Nazeh/grid-framework-behance-clone/development/index.html)

# How it works:
* use .container to define a grid row divided to 120 column.
* use .cell for each child of container to ensure spanning the whole width of the row by default and add horizontal gutters.
* define the width of each cell by giving it a class as follows: col-$break-point-$divison or col-$divison if no break points needed.
* unlike bootstrap divison defines the fraction of the row your cell's width should be, so if you want to have 3 equal columns you give each cell class="cell col-3"
* there is also left right and center classes to define justify-content property, that's why each cell has display:grid as well as the container.

# Installation:
* download stylesheets folder in the assets folder, open scss files and modify them if you want, compile base.scss and link the base.css in your html.

# Authors
* Ar Nazeh https://github.com/Nazeh
* Abdusaid10 https://github.com/Abdusaid10