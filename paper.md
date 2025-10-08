---
lang: en
layout: default
title: Paper - Interstella Project
author: Zhang Jialin
---

<div class="container">
  <h1 class="text-center mb-5">{{ site.data.i18n[site.lang].pages.paper.title }}</h1>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.paper.download }}</h2>
    <p>Full paper (v1.0): <a href="/assets/papers/interstella-paper-v1.pdf" class="btn btn-primary" download>Download PDF</a></p>
    <p class="text-muted">The complete manuscript detailing the Token Cosmos framework. Currently under review for NeurIPS 2025.</p>
  </section>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.paper.outline }}</h2>

    <h3>Abstract</h3>
    <p>We introduce Interstella, a novel framework for traversing semantic black holes in the token cosmos of large language models to elicit emergent AGI behaviors. Drawing from differential geometry and random dynamical systems, we model traversals as geodesics in information manifolds, enabling AHA moments through probabilistic reachability. Inspired by <em>Interstellar</em>, this work engineers paths to AGI/ASI via controlled leaps across semantic voids.</p>

    <h3>1. Introduction</h3>
    <p>Motivation from <em>Interstellar</em>'s themes of exploration beyond known boundaries. Challenges in LLMs: stuck in local minima of semantic spaces, hallucinations as event horizons. Our approach: Engineer traversals for continuous emergence.</p>

    <h3>2. Related Work</h3>
    <ul>
      <li>Geometric Deep Learning: Bronstein et al. (2021)</li>
      <li>Neural ODEs: Chen et al. (2018)</li>
      <li>Emergence in LLMs: Wei et al. (2022)</li>
      <li>Morse Theory in AI: Milnor (1963)</li>
      <li>Large Deviations: Freidlin & Wentzell (1998)</li>
    </ul>

    <h3>3. Mathematical Foundations</h3>
    <p>Detailed definitions, theorems (Hopf-Rinow, Freidlin-Wentzell), Fisher metric, Morse theory for critical points in semantic manifolds.</p>
    <!-- Placeholder for Figure -->
    <figure class="text-center mb-4">
      <img src="/assets/images/fisher-metric.png" alt="Fisher information metric on semantic manifold" class="img-fluid" style="max-width: 600px; box-shadow: 0 0 20px rgba(0,212,255,0.5);" />
      <figcaption>Figure 1: Fisher metric curvature in token embedding space.</figcaption>
    </figure>

    <h3>4. Framework</h3>
    <p>Token Cosmos model, traversal operators (geodesics as journeys), AHA detection via topology changes – wormholes for attention shortcuts.</p>

    <h3>5. Methodology</h3>
    <p>5-layer pipeline: Implementation details, algorithms for trajectory generation (Neural ODEs), verification (safety checks).</p>

    <h3>6. Experiments</h3>
    <p>Simulations on toy manifolds, LLM case studies (Qwen/GPT-like), metrics for emergence (AHA rate, path efficiency).</p>

    <h3>7. Discussion</h3>
    <p>Implications for AGI safety, ethical considerations in semantic exploration – aligning traversals with human values.</p>

    <h3>8. Risks and Limitations</h3>
    <p>Potential unintended emergences, computational costs, biases in traversals – safeguards via verifier layer.</p>

    <h3>9. Conclusion</h3>
    <p>Path forward: Scaling to larger models, integration with RLHF for aligned AGI engineering.</p>
  </section>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.paper.citations }}</h2>
    <p>Cite this work as:</p>
    <pre><code>@article{interstella2025,
  title={Interstella: Token Cosmos Traversal for AGI Emergence},
  author={Zhang, Jialin},
  journal={arXiv preprint arXiv:2510.XXXXX},
  year={2025}
}</code></pre>

    <h3>References (BibTeX)</h3>
    <pre><code>@inproceedings{bronstein2021geometric,
  title={Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges},
  author={Bronstein, Michael and Bruna, Joan and Cohen, Taco and Veli{\v{c}}kovi{\'c}, Petar},
  booktitle={Quarterly of Applied Mathematics},
  year={2021}
}

@article{chen2018neural,
  title={Neural Ordinary Differential Equations},
  author={Chen, Ricky T. Q. and Rubanova, Yulia and Bettencourt, Jesse and Duvenaud, David},
  journal={Advances in Neural Information Processing Systems},
  year={2018}
}

@article{wei2022emergent,
  title={Emergent Abilities of Large Language Models},
  author={Wei, Jason and Tay, Yi and Bommasani, Rishi and Raffel, Colin and Zoph, Barret and Duarte, Sebastian and Yang, Michael and Su, Xi and Dathathri, S and Shazeer, Noam and others},
  journal={Transactions on Machine Learning Research},
  year={2022}
}

@book{milnor1963morse,
  title={Morse Theory},
  author={Milnor, John},
  year={1963},
  publisher={Princeton University Press}
}

@book{freidlin1998random,
  title={Random Perturbations of Dynamical Systems},
  author={Freidlin, Mark I and Wentzell, Alexander D},
  year={1998},
  publisher={Springer}
}</code></pre>
  </section>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.paper.updates }}</h2>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">October 2025: Initial Draft</h5>
        <p class="card-text">Project launched with preliminary results and open-source code.</p>
      </div>
    </div>
    <div class="card mt-3">
      <div class="card-body">
        <h5 class="card-title">Submitted to NeurIPS 2025</h5>
        <p class="card-text">Under review. Decision expected December 2025. Track updates on arXiv.</p>
      </div>
    </div>
  </section>
</div>
