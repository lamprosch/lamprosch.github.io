---
layout: default
title: Guitar & Music Theory Lessons
permalink: /lessons/
---

<section class="container">
  <h1>Guitar & Music Theory Lessons</h1>
  
  <section class="home-hero">
    <div class="hero-text">
      <h2>Learn Music from a Passionate Educator</h2>
      <p>I studied classical guitar extensively and have deep knowledge in music theory fundamentals and advanced concepts. I teach guitar and music theory with a practical, student-focused approach tailored to your goals, your pace, and the music you love.</p>
      
      <h3>My Teaching Approach</h3>
      <ul>
        <li>Personalized lesson plan based on your level</li>
        <li>Focus on technique, musicality, and confidence</li>
        <li>Clear explanations of theory without unnecessary complexity</li>
        <li>Exercises, recordings, and progress tracking</li>
        <li>Suitable for beginners and intermediate players</li>
      </ul>
    </div>
  </section>

  <section>
    <h2>Enquire About Lessons</h2>
    <p>Fill out the form below to let me know about your interests and experience level. I'll get back to you soon with details about availability and pricing.</p>
    
    <form action="https://formspree.io/f/xyzqrwlb" method="POST">
      <div class="form-row">
        <div>
          <label for="firstName">First Name</label>
          <input type="text" id="firstName" name="firstName" required>
        </div>
        <div>
          <label for="lastName">Last Name</label>
          <input type="text" id="lastName" name="lastName" required>
        </div>
      </div>

      <div>
        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required>
      </div>

      <div>
        <label for="location">Location</label>
        <input type="text" id="location" name="location" placeholder="City, Country or Online">
      </div>

      <div class="form-row">
        <div>
          <label for="preference">Lesson Type Preference</label>
          <select id="preference" name="preference" required>
            <option value="">Select...</option>
            <option value="guitar">Guitar Lessons</option>
            <option value="music-theory">Music Theory</option>
            <option value="both">Both Guitar & Theory</option>
          </select>
        </div>

        <div>
          <label for="experience">Experience Level</label>
          <select id="experience" name="experience" required>
            <option value="">Select...</option>
            <option value="beginner">Beginner</option>
            <option value="intermediate">Intermediate</option>
            <option value="advanced">Advanced</option>
          </select>
        </div>
      </div>

      <div>
        <label for="message">Message (Optional)</label>
        <textarea id="message" name="message" placeholder="Tell me about your musical goals or any questions you have..."></textarea>
      </div>

      <button type="submit" class="btn">Send Enquiry</button>
    </form>
  </section>
</section>
