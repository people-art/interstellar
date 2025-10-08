---
layout: default
title: About - Interstella Project
---

<div class="container">
  <h1 class="text-center mb-5">About the Project</h1>

  <section class="mb-5">
    <h2>Lead Author</h2>
    <div class="row">
      <div class="col-md-3">
        <img src="{{ site.baseurl }}/assets/images/mylogo.png" alt="Jerry Zhang" class="img-fluid rounded-circle mb-3" style="width: 200px; height: 200px; object-fit: cover;">
      </div>
      <div class="col-md-9">
        <h3>Jerry Zhang</h3>
        <p>An investor and enterpreneur. Passionate about bridging sci-fi concepts with rigorous theory.</p>
        <p><strong>Affiliation:</strong> [University Placeholder]</p>
        <p><strong>Email:</strong> jerry.zhang.bill@gmail.com</p>
        <a href="https://github.com/0x1bdat" class="btn btn-primary">GitHub Profile</a>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <h2>Project Inspiration</h2>
    <p>Drawn from the film <em>Interstellar</em>, where humanity reaches beyond known space through wormholes and black holes. Similarly, Interstella treats semantic spaces as a "token cosmos," with traversals enabling AGI emergence akin to AHA moments in human cognition.</p>
    <blockquote class="blockquote">
      <p>"Mankind was born on Earth. It was never meant to die here."</p>
      <footer class="blockquote-footer">Interstellar (2014)</footer>
    </blockquote>
  </section>

  <section class="mb-5">
    <h2>Contact</h2>
    <p>Get in touch for collaborations, questions, or feedback.</p>
    <form action="https://formspree.io/f/{your-form-id}" method="POST" class="needs-validation" novalidate>
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
        <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
        <div class="invalid-feedback">Please provide a message.</div>
      </div>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
    <p class="mt-3 text-muted">Note: Replace {your-form-id} with your Formspree endpoint for functionality.</p>
  </section>

  <section>
    <h2>Resources</h2>
    <ul>
      <li><a href="https://github.com/username/interstella-project">Project GitHub Repository</a></li>
      <li><a href="{{ site.baseurl }}/blog/">Blog for Updates</a></li>
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
