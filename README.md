<h1 align="center">Welcome to Behance Clone 👋</h1>
<p>
  <a href="https://github.com/Nazeh/grid-framework-behance-clone/blob/master/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://twitter.com/arnazeh" target="_blank">
    <img alt="Twitter: arnazeh" src="https://img.shields.io/twitter/follow/arnazeh.svg?style=social" />
  </a>
</p>

> A clone of [Behance.net](https://www.behance.net/) website page, as a demonstration of a custom grid based SASS framework.

### ✨ [Demo](https://nazeh.github.io/grid-framework-behance-clone/)

<img alt='screenshot' src='docs/screenshot.webp'>

## Install

Download [layout.css](assets/stylesheets/layout.css) or [layout.scss](assets/stylesheets/layout.scss), and link it in your project.

## Usage

* use .container to define a grid row divided to 120 columns.
* use .cell for each child of container to ensure spanning the whole width of the row by default and add horizontal gutters.
* define the width of each cell by giving it a class as follows: col-$break-point-$divison or col-$divison if no breakpoints needed.
* unlike bootstrap, division defines the fraction of the row your cell's width should be, so if you want to have 3 equal columns you give each cell class="cell col-3"
* there is also left right and center classes to define the justify-content property, that's why each cell has display: grid as well as the container.

## Author

👤 **Nazeh**

* Website: nazeh.me
* Twitter: [@arnazeh](https://twitter.com/arnazeh)
* Github: [@nazeh](https://github.com/nazeh)
* LinkedIn: [@arnazeh](https://linkedin.com/in/arnazeh)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Nazeh/grid-framework-behance-clone/issues). 

## Show your support

Give a ⭐️ if this project helped you!
