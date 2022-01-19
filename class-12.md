# Read: 12 - Docs for the HTML `<canvas>` Element & Chart.js

## Chart.js API

- `Chart.js` is an element that allows us to draw graphs on the page
- It can make different charts such as bar charts, line charts, pie charts etc..
- Chart.js is simple to use and it is very flexible
- `<canvas>` renders the chart

### Stepts to Drawing a Line Chart

1. On the body of out HTML page add this:\
`canvas id id =" " width = " " height = " "></canvas>`

2. To retrive the context on the foot of the body element add this:\
`<script>\var buyers = document.getElementById('buyers').getContext('2d');new Chart(buyers).Line(buyerData);</script>`

3. We then have to create our data for example we can add labels of our chart by:\
`var buyerData = {\labels : ["January","February","March","April","May","June"],datasets : ] {`

### Drwaing a Pie Chart

1. Follow the same two steps of drawing a line chart
2. Supply a value and color for each section of the pie chart eg:\
`var pieData = {value: 20,color:"#878BB6"},`

3. After the pieData we then add our options eg:\
`var pieOptions = {segmentShowStroke : false,animateScale : true}`

### Drawing a Bar Chart

- Follow the same steps as drawing a line chart excpt for the colors we choose RGBA becaause it allows us to add transparency
