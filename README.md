### Enhanced-FlexGrid

- The width of each column is 25% of the window size.
- This width must be maintained even if the page is resized. Also make sure that each cell of the grid can contain another 1x4 flexible grid.
- If the window size is less than 720px, then the 1x4 flexible grid becomes a 2x2 grid, that is, the 3rd and 4th columns slide down onto the 2nd row.
- If the window size is less than 360px, then the 1x4 flexible grid becomes 4x1 grid, that is, each column slides under the one before it. The 2nd column slides under the 1st, the 3rd slides under the 2nd, and the 4th slides under the 3rd.

### Example Screenshots (All using google chrome)

#Full Width / View

![Alt text](/screenshots/full-width.png?raw=true "Full Width")

#Less than 720px 

![Alt text](/screenshots/720px.png?raw=true "Less than 720px")

#Less than 360px (Using chrome dev tools to get a window width less than 36opx)

![Alt text](/screenshots/360px.png?raw=true "Less than 360px")