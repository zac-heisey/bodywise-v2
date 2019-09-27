---
title: Contact Us
layout: page
subtitle: Schedule an Appointment or Get in Touch with Us in Boulder, Broomfield,
  or Westminster
description: Contact the team at Bodywise Physical Therapy to schedule your appointment
  in Boulder, Broomfield, or Westminster today.
sidebar: false

---
<!-- Google reCAPTCHA -->
<script src="https://www.google.com/recaptcha/api.js" async defer></script>

<!-- Bodywise PT Contact Form (via Basin) -->
<form accept-charset="UTF-8" name="Bodywise PT Contact Form" action="https://usebasin.com/f/e1ce584f529c" enctype="multipart/form-data" method="POST">
  <div class="row">
    <div class="col-6 col-12-medium col-12-small">
      <label for="name">Your Name</label>
      <input type="text" name="name" id="name" required>

      <label for="phone">Your Phone Number</label>
      <input type="tel" name="phone" id="phone" required>

      <label for="email">Your Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="message">How Can We Help?</label>
      <textarea name="comment" id="message" required></textarea>
    </div>
    <div class="col-6 col-12-medium col-12-small">
      <label for="locations">Select a Location</label>
      <select class="locations" name="locations" id="locations" required>
        <option value="" disabled selected>-- Choose Location --
        <option value="Boulder">Boulder</option>
        <option value="Broomfield">Broomfield</option>
        <option value="Westminster">Westminster</option>
      </select>

      <label for="date">Preferred Appointment Date (optional)</label>
      <input type="date" name="date" id="date">

      <label for="time">Preferred Appointment Time (optional)</label>
      <select class="time" name="time" id="time">
        <option value="Morning">Morning</option>
        <option value="Afternoon">Afternoon</option>
        <option value="Evening">Evening</option>
      </select>

      <label for="confirm">Connect With Us!</label>
      <div class="g-recaptcha" data-sitekey="6Lew3SMUAAAAAJ82QoS7gqOTkRI_dhYrFy1f7Sqy"></div>

      <button type="submit" class="button primary">Get In Touch</button>
    </div>
  </div>  
</form>
