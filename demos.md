---
layout: default
title: Demonstrations - Interstella Project
---

<div class="container">
  <h1 class="text-center mb-5">Interactive Demonstrations</h1>
  <p class="lead text-center mb-5">Explore visualizations of token trajectories, uncertainty landscapes, and AHA detections.</p>

  <section class="mb-5">
    <h2>Token Trajectories</h2>
    <div class="row">
      <div class="col-md-6">
        <img src="{{ site.baseurl }}/assets/images/trajectory-visual.jpg" alt="Token trajectory in semantic space" class="img-fluid rounded mb-3" style="box-shadow: 0 0 20px rgba(0,212,255,0.5);">
        <p>Visualization of geodesic paths connecting semantic regions, simulating leaps to emergent insights.</p>
      </div>
      <div class="col-md-6">
        <p>Interactive Plotly demo: Drag to explore the manifold.</p>
        <div id="trajectory-plot" style="height: 400px; background: rgba(0,0,0,0.5);"></div>
        <a href="https://github.com/username/TC_AEOT_Integrated/blob/main/trajectory_demo.ipynb" class="btn btn-primary mt-2">View Jupyter Notebook</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>Uncertainty Landscapes</h2>
    <div class="row">
      <div class="col-md-6">
        <img src="{{ site.baseurl }}/assets/images/uncertainty-heatmap.jpg" alt="Uncertainty heatmap in token cosmos" class="img-fluid rounded mb-3" style="box-shadow: 0 0 20px rgba(0,212,255,0.5);">
        <p>Heatmap showing regions of high uncertainty, potential black holes in semantic space.</p>
      </div>
      <div class="col-md-6">
        <video width="100%" controls>
          <source src="{{ site.baseurl }}/assets/videos/aha-moment.gif" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <p>AHA detection in simulation: Sudden insight emergence.</p>
        <a href="https://github.com/username/TC_AEOT_Integrated/blob/main/uncertainty_analysis.ipynb" class="btn btn-primary mt-2">Code Demo</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>Vector Fields</h2>
    <div class="row">
      <div class="col-md-12">
        <img src="{{ site.baseurl }}/assets/images/vector-field.jpg" alt="Vector field guiding traversals" class="img-fluid rounded mx-auto d-block mb-3" style="max-width: 800px; box-shadow: 0 0 20px rgba(0,212,255,0.5);">
        <p>Flow lines representing dynamical system evolution towards emergent manifolds.</p>
        <a href="https://github.com/username/TC_AEOT_Integrated" class="btn btn-primary">Full Code Repository</a>
      </div>
    </div>
  </section>

  <p class="text-center">For more interactive elements, check the GitHub repo. Embed codes for Plotly and other JS libraries can be added for full interactivity.</p>
</div>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
// Placeholder for Plotly plot
var data = [{ z: [[1, 20, 30], [20, 1, 60], [30, 60, 1]], type: 'surface' }];
Plotly.newPlot('trajectory-plot', data);
</script>
