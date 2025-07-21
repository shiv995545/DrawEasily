# DrawEasily
DrawEasily is a browser-based sketching tool that allows users to draw on a canvas using various tools like brush, eraser, shapes (rectangle, circle, triangle), and color selection. It provides options to customize brush size, fill shapes, clear the canvas, and download the drawing as an image.


----Key Features----

--Canvas Drawing:

* Users can draw freehand with a brush or erase.
* Supports drawing geometric shapes: rectangle, circle, triangle.
* Shapes can be filled or outlined based on a toggle.


--Tool Options:

* Brush and Eraser
* Shapes with fill option
* Adjustable brush size via slider


--Color Selection:

* Multiple predefined colors
* Custom color picker for advanced selection


--Canvas Controls:

* Clear Canvas: Erases all drawings and resets the background.
* Save as Image: Downloads the current canvas as a .jpg image.



----File Breakdown----

--index.html:
* Structures the UI, including the tool panel and drawing canvas. Connects to CSS and JavaScript.

--style.css:
* Handles responsive layout and styling for tools, canvas, color palette, and buttons using modern CSS (Flexbox, custom fonts, etc.).

--script.js:
* Implements the core functionality:
* Drawing logic for each tool
* Color/size/shape handling
* Event listeners for mouse actions
* Image saving and canvas reset logic

