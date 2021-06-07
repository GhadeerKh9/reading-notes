# Charts  


**Drawing a line chart**  

* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 

* Next, we need to write a script that will retrieve the context of the canvas.
Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

# The <canvas> element

* Canvas is like img, but the mainly difference is that it has only two attributes, which are height and width.
* It requires a closing tag unlike the image element.

* Browsers that do support <canvas> will ignore the content inside the container, and just render the canvas normally.


# Drawing Rectangles

**These functions are used to draw rectangles on the canvas:**
* fillRect(x, y, width, height): Draws a filled rectangle.
* strokeRect(x, y, width, height): Draws a rectangular outline.
* clearRect(x, y, width, height) : Clears the specified rectangular area, making it fully transparent.


**Drawing path**

**functions used to create paths:**

* beginPath() : Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
* Path methods: Methods to set different paths for objects.
* closePath(): Adds a straight line to the path, going to the start of the current sub-path.
* stroke(): Draws the shape by stroking its outline.
* fill(): Draws a solid shape by filling the path's content area.

## Colors:


**color is a string representing a CSS <color>, a gradient object, or a pattern object.**

**properties we can use to apply colours to a shape:**

* fillStyle = color : Sets the style used when filling shapes.
* strokeStyle = color: Sets the style for shapes' outlines.
