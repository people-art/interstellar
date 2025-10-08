---
lang: en
layout: default
title: Demonstrations - Interstella Project
---

<div class="container">
  <h1 class="text-center mb-5">Interactive Demonstrations</h1>
  <p class="lead text-center mb-5">Explore visualizations of token trajectories, uncertainty landscapes, and AHA detections in the Token Cosmos.</p>

  <section class="mb-5">
    <h2>Token Trajectories</h2>
    <div class="row">
      <div class="col-md-6">
        <img src="/assets/images/trajectory-bundle.png" alt="Visualization of token trajectories in semantic space, showing bundled paths leaping across manifolds" class="img-fluid rounded mb-3" style="box-shadow: 0 0 20px rgba(0,212,255,0.5);" />
        <p>Visualization of geodesic paths connecting semantic regions, simulating leaps to emergent insights – like charting a course through wormholes.</p>
      </div>
      <div class="col-md-6">
        <p>Interactive Plotly demo: Drag to explore the manifold traversal.</p>
        <div id="trajectory-plot" style="height: 400px; background: rgba(0,0,0,0.5); border: 1px solid #00d4ff;"></div>
        <a href="https://github.com/people-art/interstellar/blob/main/TC_AEOT_Integrated_AHA_Final.ipynb" class="btn btn-primary mt-2">View Jupyter Notebook on GitHub</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>Uncertainty Landscapes</h2>
    <div class="row">
      <div class="col-md-6">
        <img src="/assets/images/uncertainty-heatmap.png" alt="Heatmap of uncertainty regions in the token cosmos, highlighting potential semantic black holes" class="img-fluid rounded mb-3" style="box-shadow: 0 0 20px rgba(0,212,255,0.5);" />
        <p>Heatmap showing regions of high uncertainty, potential black holes in semantic space where innovation hides.</p>
      </div>
      <div class="col-md-6">
        <video width="100%" controls preload="metadata">
          <source src="/assets/videos/aha-moment.gif" type="video/mp4" />
          Your browser does not support the video tag. <a href="/assets/videos/aha-moment.gif">Download GIF</a>
        </video>
        <p>AHA detection in simulation: Sudden insight emergence as a trajectory escapes a local minimum.</p>
        <a href="https://github.com/people-art/interstellar/blob/main/uncertainty_analysis.ipynb" class="btn btn-primary mt-2">Run Code Demo on GitHub</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>Vector Fields</h2>
    <div class="row">
      <div class="col-md-12">
        <img src="/assets/images/vector-field.png" alt="Vector field guiding traversals in semantic space, showing flow lines toward emergent regions" class="img-fluid rounded mx-auto d-block mb-3" style="max-width: 800px; box-shadow: 0 0 20px rgba(0,212,255,0.5);" />
        <p>Flow lines representing dynamical system evolution towards emergent manifolds – the gravitational pull of novel ideas.</p>
        <a href="https://github.com/people-art/interstellar" class="btn btn-primary">Full Code Repository</a>
      </div>
    </div>
  </section>

  <p class="text-center">For more interactive elements, check the GitHub repo. Embed codes for Plotly and other JS libraries enable full interactivity in future updates.</p>
</div>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>

<script>
  // Enhanced Plotly plot for trajectory demo
  var trace = {
    x: [0, 1, 2, 3, 4],
    y: [0, 2, 1, 3, 2.5],
    mode: 'lines+markers',
    type: 'scatter',
    name: 'Semantic Traversal Path',
    line: { color: '#00d4ff', width: 3 },
    marker: { size: 8, color: '#00d4ff' }
  };
  var layout = {
    title: 'Token Trajectory in Semantic Manifold',
    xaxis: { title: 'Step' },
    yaxis: { title: 'Embedding Distance' },
    plot_bgcolor: 'rgba(0,0,0,0.8)',
    paper_bgcolor: 'rgba(0,0,0,0.8)',
    font: { color: '#ffffff' }
  };
  var data = [trace];
  Plotly.newPlot('trajectory-plot', data, layout);
</script>
