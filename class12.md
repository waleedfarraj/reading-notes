# Read: 12 - Docs for the HTML canvas-tags Element & Chart.js


Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
```

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>

```
after downloading the .zip that containts this file Chart.min.js you can link it to you html and then use the ``` <canvas>``` tag .
Drawing a line chart

To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

```<canvas id="buyers" width="600" height="400"></canvas>```
to write a script that will retrieve the context of the canvas use this:


```
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
``` 
and there is many types of charts and how to style them from line charts to pie chats .you can also draw using the x and y and z axis coordinates .


