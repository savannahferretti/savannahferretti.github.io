---
layout: default
title: Contact
permalink: /contact/
---

<div class="contact-layout">

  <div class="contact-intro">
    <h2>Get in Touch</h2>
    <p>
      Feel free to reach out about research, collaboration, or industry opportunities.
      I try to reply within a few days.
    </p>
    <p>
      You can also find me at:<br>
      <strong>Room 000, Gates Hall</strong><br>
      Example University<br>
      New York, NY 10000
    </p>
    <p>
      <a href="mailto:sferretti@example.edu">sferretti@example.edu</a>
    </p>
  </div>

  <div class="contact-form-wrap">
    <form
      class="contact-form"
      action="https://formspree.io/f/YOUR_FORM_ID"
      method="POST"
    >
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name" required>
      </div>

      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="your@email.com" required>
      </div>

      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="6" placeholder="Your message…" required></textarea>
      </div>

      <button type="submit" class="form-submit">Send</button>
    </form>
  </div>

</div>
