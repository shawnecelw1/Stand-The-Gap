---
layout: page
title: Contact
permalink: /contact/
---

If you’d like to connect, please submit the form below and we’ll respond as soon as possible.

<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <label>
    Your name<br>
    <input type="text" name="name" required>
  </label>
  <br><br>

  <label>
    Your email<br>
    <input type="email" name="email" required>
  </label>
  <br><br>

  <label>
    Subject<br>
    <input type="text" name="subject">
  </label>
  <br><br>

  <label>
    Message<br>
    <textarea name="message" rows="6" required></textarea>
  </label>
  <br><br>

  <!-- Optional: prevents spam bots -->
  <input type="text" name="_gotcha" style="display:none">

  <button type="submit">Send Message</button>
</form>
