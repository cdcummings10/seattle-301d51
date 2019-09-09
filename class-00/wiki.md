#GRIDS

Grids are a widely useful css tool for creating columns and rows on a site. Floats are still the primary method of alignment in most cases, but as the years go by grid gets more popular.

##How To Use Grids

###Parent
You'll first have to assign a parent element for the grid. This will house individual grid blocks:

.container {
  display: grid | inline-grid;
}

You'll then need to define certain attributes for the grid with grid specific CSS (i.e. grid-template-columns, grid-template-rows, etc.).

###Children
The children of the grid parent will need specific styling if they go outside of the grid specifics defined in the parent.

Note: float, display: inline-block, display: table-cell, vertical-align and column-* properties have no effect on a grid item.


###More References
For a more in-depth run down of all the grid properties and how they interact with each other, check out:

CSS-tricks: https://css-tricks.com/snippets/css/complete-guide-grid/#grid-introduction