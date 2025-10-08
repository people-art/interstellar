---
title: Token Trajectory Visualization
category: demos
---

<h2>Interactive Token Trajectory</h2>
<p>This demo shows a sample trajectory in a 2D semantic manifold.</p>
<div id="demo-plot" style="height: 500px;"></div>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
var trace = {
  x: [1, 2, 3, 4],
  y: [10, 15, 13, 17],
  type: 'scatter',
  mode: 'lines+markers',
  name: 'Trajectory'
};
var data = [trace];
Plotly.newPlot('demo-plot', data);
</script>

<p>Link to full notebook: <a href="https://github.com/username/notebook">GitHub</a></p>
