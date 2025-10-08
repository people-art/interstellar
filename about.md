---
lang: en
layout: default
title: About - Interstella Project
author: Zhang Jialin
---

<div class="container">
  <h1 class="text-center mb-5">{{ site.data.i18n[site.lang].pages.about.title }}</h1>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.about.lead_author }}</h2>
    <div class="row">
      <div class="col-md-3">
        <img src="{{ site.baseurl }}/assets/images/mylogo.png" alt="Zhang Jialin" class="img-fluid rounded-circle mb-3" style="width: 200px; height: 200px; object-fit: cover;">
      </div>
      <div class="col-md-9">
        <h3>Zhang Jialin</h3>
        <p>Researcher in AGI and applications of differential geometry to AI. Passionate about engineering emergent intelligence through semantic traversals, bridging sci-fi inspiration from <em>Interstellar</em> with rigorous mathematical frameworks. Leading the Interstella project since October 2025, focusing on controllable LLM reasoning and paths to ASI.</p>
        <p><strong>Email:</strong> jerry.zhang.bill@gmail.com</p>
        <a href="https://github.com/0x1bdat" class="btn btn-primary">GitHub Profile</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.about.inspiration }}</h2>
    <p>Drawn from the film <em>Interstellar</em>, where humanity reaches beyond known space through wormholes and black holes. Similarly, Interstella treats semantic spaces as a "token cosmos," with traversals enabling AGI emergence akin to AHA moments in human cognition.</p>
    <blockquote class="blockquote">
      <p>"Mankind was born on Earth. It was never meant to die here."</p>
      <footer class="blockquote-footer">Interstellar (2014)</footer>
    </blockquote>
  </section>

  <section class="mb-5">
    <h2>Project Timeline</h2>
    <ul>
      <li><strong>October 2025:</strong> Project launch with initial framework and open-source repo.</li>
      <li><strong>November 2025:</strong> First experiments on Qwen model traversals.</li>
      <li><strong>December 2025:</strong> NeurIPS submission and community contributions.</li>
      <li><strong>Ongoing:</strong> Building the 5-layer pipeline for aligned AGI engineering.</li>
    </ul>
  </section>

  <section class="mb-5">
    <h2>Featured Launch Article</h2>
    <h3>Welcome to Interstella: Traversing the Token Cosmos to AGI's Interstellar Journey</h3>
    <p>Read our inaugural post introducing the project's origins, short-term goals for LLM optimization, and long-term vision for AGI/ASI. [Link to blog post]</p>
  </section>

  <section class="mb-5">
    <h2>{{ site.data.i18n[site.lang].pages.about.contact }}</h2>
    <p>Get in touch for collaborations, questions, feedback, or to discuss AGI ethics.</p>
    <form action="https://formspree.io/f/xqkvzqen" method="POST" class="needs-validation" novalidate> <!-- Replace with your real Formspree endpoint -->
      <div class="mb-3">
        <label for="name" class="form-label">Name</label>
        <input type="text" class="form-control" id="name" name="name" required>
        <div class="invalid-feedback">Please provide your name.</div>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" name="email" required>
        <div class="invalid-feedback">Please provide a valid email.</div>
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" name="message" rows="5" required placeholder="Tell us about your interest in Interstella..."></textarea>
        <div class="invalid-feedback">Please provide a message.</div>
      </div>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
    <p class="mt-3 text-muted">Powered by Formspree – responses sent to project email.</p>
  </section>

  <section class="mb-5">
    <h2>Ethics and AGI Safety</h2>
    <p>Interstella is committed to safe AGI development. Key principles:</p>
    <ul>
      <li><strong>Alignment:</strong> Verifier layer ensures traversals align with human values, mitigating hallucinations and biases.</li>
      <li><strong>Risks:</strong> Potential for unintended emergence; we incorporate human-in-the-loop safeguards and ethical reviews.</li>
      <li><strong>Community:</strong> Open discussions on risks like misalignment or misuse – contribute via GitHub issues.</li>
    </ul>
  </section>

  <section>
    <h2>{{ site.data.i18n[site.lang].pages.about.resources }}</h2>
    <ul>
      <li><a href="https://github.com/people-art/interstella">Project GitHub Repository</a></li>
    </ul>
  </section>
</div>

<script>
// Bootstrap form validation
(function () {
  'use strict'
  var forms = document.querySelectorAll('.needs-validation')
  Array.prototype.slice.call(forms).forEach(function (form) {
    form.addEventListener('submit', function (event) {
      if (!form.checkValidity()) {
        event.preventDefault()
        event.stopPropagation()
      }
      form.classList.add('was-validated')
    }, false)
  })
})()
</script>
