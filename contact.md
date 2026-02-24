---
layout: default
title: Contact
permalink: /contact/
---

<section class="container">
  <h1>Get In Touch</h1>
  <p class="meta">Have questions or want to collaborate? I'd love to hear from you.</p>

  <section>
    <h2>Connect With Me</h2>
    <p>Find me on social media or send me a message using the form below.</p>
    
    <div style="margin: var(--space-lg) 0; display: flex; gap: var(--space-lg); flex-wrap: wrap;">
      <a href="https://twitter.com" class="btn">Twitter</a>
      <a href="https://music.apple.com" class="btn">Apple Music</a>
      <a href="https://github.com" class="btn">GitHub</a>
    </div>
  </section>

  <section>
    <h2>Send Me a Message</h2>
    <p>For inquiries about mixing, engineering, or teaching, please fill out the form below.</p>
    
    <form action="https://formspree.io/f/xyzqrwlc" method="POST">
      <div class="form-row">
        <div>
          <label for="contactFirstName">First Name</label>
          <input type="text" id="contactFirstName" name="firstName" required>
        </div>
        <div>
          <label for="contactLastName">Last Name</label>
          <input type="text" id="contactLastName" name="lastName" required>
        </div>
      </div>

      <div>
        <label for="contactEmail">Email Address</label>
        <input type="email" id="contactEmail" name="email" required>
      </div>

      <div>
        <label for="subject">Subject</label>
        <select id="subject" name="subject" required>
          <option value="">Select...</option>
          <option value="mixing">Mixing / Engineering Inquiry</option>
          <option value="collaboration">Collaboration</option>
          <option value="other">Other</option>
        </select>
      </div>

      <div>
        <label for="contactMessage">Message</label>
        <textarea id="contactMessage" name="message" required placeholder="Your message here..."></textarea>
      </div>

      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <section>
    <h2>Direct Contact</h2>
    <p><strong>Email:</strong> <a href="mailto:lampros.chantzis@outlook.com">lampros.chantzis@outlook.com</a></p>
  </section>
</section>
