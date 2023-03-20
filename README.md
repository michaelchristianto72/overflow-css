# overflow-css

study case for overflow css

overflow: props that controls what happens to content is too big to fit into an area (w3schools)
in other words, overflow happens when the child (content) is too large than the parent (area)

In this study case, i want to make an image/icon that can go through the top of the table. (using absolute position) but the table's width is to big, so i need to use overflow-x to make the table scrollable. But my image is cropped because of the height

solution:
because the overflow meaning is "too large", my parent height isn't smaller than the child, so the parent's height is the same as the child. to make the icon is "visible" at the top, my solution is using padding top in the child.
so the parent's height will be = child's height + padding-top

(i dont need to defined the height (parent) to be smaller (than the child) because i dont need the height is scrollable)
