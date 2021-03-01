# Charts
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.      
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.    
To see how to use chart.js we’re going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally we’ll use a bar chart to show profit over the period.    
## Drawing a line chart   
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:    
`<canvas id="buyers" width="600" height="400"></canvas>`

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:    
`<script>`
    var buyers = document.getElementById('buyers').getContext('2d');    
    new Chart(buyers).Line(buyerData);     
`</script>`
Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’:    
var buyerData = {      
	labels : ["January","February","March","April","May","June"],      
	datasets : [      
		{      
			fillColor : "rgba(172,194,132,0.4)",      
			strokeColor : "#ACC26D",      
			pointColor : "#fff",      
			pointStrokeColor : "#9DB86D",      
			data : [203,156,99,251,305,247]      
		}      
	]      
}         
## Drawing a pie chart    
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:     
`<canvas id="countries" width="600" height="400"></canvas>`      
Next, we need to get the context and to instantiate the chart:     
var countries= document.getElementById("countries").getContext("2d");      
new Chart(countries).Pie(pieData, pieOptions);        

## Drawing a bar chart      
Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:     
`<canvas id="income" width="600" height="400"></canvas>`     
Next, we retrieve the element and create the graph:     
var income = document.getElementById("income").getContext("2d");      
new Chart(income).Bar(barData);    

The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options     
At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.     
The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture> `elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.      
The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context      
## Checking for support    
The fallback content is displayed in browsers which do not support `<canvas>`. Scripts can also check for support programmatically by testing for the presence of the getContext() method. Our code snippet from above     
## The grid    
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.     
## Drawing rectangles     
Unlike SVG, `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.      
## Drawing paths     
Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:     
1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.      