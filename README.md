# Pixel Art Maker
by Brian Lee

A pixel art maker written with HTML5, CSS3 and native JavaScript (ES6).

### Table of Contents
- Description
- Timeline
- Daily Log


#### Description

This site incorporates a simple pixel art maker. Features include:
- Ability to configure size of grid
- Custom colors
- Drawing on multiple cells by dragging
- Cursor that reflects the current color
- 'Undo' by pressing shift
- Overlay blending by pressing alt

Instead of recycling/resetting style attributes of the div elements used in the grid, this site creates and appends layers of colors and nests them within the div structures. While this has the side effect of increased resources required to run the site, it is necessary for the 'undo' feature since the html structure will contain data of all the layers that has previously been applied to each cell. I anticipate that this can be simplified with better ways to store and recall data than the current method. Similarly, because of limitations involved in using native JS to accomplish these tasks, the site may require more resource than otherwise necessary.

#### Timeline
Started: Nov. 11, 2016

Due: Nov. 14, 2016

#### Daily log
##### Day 1
###### progress:
 * generate html/css for basis
 * click div elements to add divs, shift+click to remove(undo)
 * alt+div enables blend mode

###### TODO:
 - drag capability (bonus 1)
 - custom color (bonus 2)

##### Day 2
###### progress:
* add cursor displays of current color
* attempt reconstructing div structure to ensure append occurs in appropriate place

###### TODO:
- drag
- custom color

##### Day 3
###### progress:
* 'drag to draw' enabled
* restructure div class to specify behavior
* custom color enabled
* grid sizing by user input enabled
* grid resizes depending on number of cells requested.
