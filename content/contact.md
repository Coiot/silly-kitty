---
title: Contact
subtitle: Sed magna in pharetra ultricies dolor sit amet consequat adipiscing lorem.
content_img:
  enabled: false
  path: ''
  url: "#"
sidebar:
  enabled: false
  side: left
layout: page
menu:
  main:
    name: Contact Us
    weight: 4
  footer:
    weight: 1

---
<form name="contactForm" method="POST" netlify-honeypot="bot-field" data-netlify="true" id="contact-form" class="contact-form">

<p class="form-row">

<label class="form-label" for="contact-user-name">Name</label>

<input type="text" name="name" id="contact-user-name" class="form-input" placeholder="Enter your name"> <span class="input-focus" aria-hidden="true"></span> </p>

<select name="demo-category" id="demo-category">
<option value="">- Category -</option>
<option value="1">Manufacturing</option>
<option value="1">Shipping</option>
<option value="1">Administration</option>
<option value="1">Human Resources</option>
</select>

<input type="radio" id="demo-priority-low" name="demo-priority">
<label for="demo-priority-low">Low</label>

<input type="radio" id="demo-priority-low" name="demo-priority" checked> <label for="demo-priority-low">Low</label>

<input type="radio" id="demo-priority-low" name="demo-priority"> <label for="demo-priority-low">Low</label>

<p class="form-row"> <label class="form-label" for="contact-user-email">Email</label> <input type="email" name="email" id="contact-user-email" class="form-input" placeholder="Enter your email address"> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-message">Message</label> <textarea name="message" id="contact-message" class="form-textarea" rows="5" placeholder="Enter your message"></textarea> <span class="input-focus" aria-hidden="true"></span> </p>

<input type="hidden" name="form-name" value="contactForm" /> <p class="form-row form-submit">

<button type="submit" class="primary button">Send Message</button> </p> </form><!-- .contact-form -->