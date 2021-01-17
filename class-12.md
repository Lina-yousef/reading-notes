**Docs for the HTML (canvas) Element & Chart.js**

Uses for displaying data visually than tables

JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.

using all kinds of bar charts, line charts, pie charts.

**how to use chart.js ?**

* Create a set of 3 graphs:

1. **Line chart** : First will show the number of buyers a fictional.
2. **Pie chart** :Second will show which countries the customers come from.
3. finally we’ll use a bar chart to show profit over the period.

**The canvas element**:

* Has two attributes: width and height.

* It is always a good idea to supply an id because this makes it much easier to identify it in a script.

* Can be styled just like any normal image (margin, border, background…).

* Element **requires** the closing tag (/canvas). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

* Rendering contexts :to create and manipulate the content shown.

**Drawing shapes with canvas** 

* There are three functions that draw rectangles on the canvas:2

1. fillRect(x, y, width, height): Draws a filled rectangle.
2. strokeRect(x, y, width, height) :Draws a rectangular outline.
3. clearRect(x, y, width, height) : Clears the specified rectangular area, making it fully transparent.

**Drawing paths:**

1. Create the path.
2. Use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

* For drawing straight lines, use the lineTo() method. (lineTo(x, y)).

* To draw arcs or circles, we use the arc() or arcTo() methods.

* If we want to apply colors to a shape, there are two important properties we can use: **fillStyle** and **strokeStyle**.

* **There are several properties which allow us to style lines:**

**lineWidth = value** :Sets the width of lines drawn in the future.
**lineCap = type**: Sets the appearance of the ends of lines.
**lineJoin = type**: Sets the appearance of the "corners" where lines meet.
**miterLimit = value**: Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
**getLineDash()**: Returns the current line dash pattern array containing an even number of non-negative numbers.
**setLineDash(segments)** :Sets the current line dash pattern.
**lineDashOffset = value** :Specifies where to start a dash array on a line.

* **The lineCap property** :determines how the end points of every line are drawn.values for this property : butt, round and square . 

* **The lineJoin property** : determines how two connecting segments (of lines, arcs or curves), values for this property :  round, bevel and miter.

**Drawing text**

* Two methods to render text:

- FillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- StrokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

* Properties which let you adjust the way the text gets displayed on the canvas:

- font = value
- textAlign = value
- textBaseline = value
- direction = value


[Previous](class-11.md)  | [Home](README.md) | [Next](class-13.md)
