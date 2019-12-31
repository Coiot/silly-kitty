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
    weight: 3

---
<form name="contactForm" method="POST" netlify-honeypot="bot-field" data-netlify="true" id="contact-form" class="contact-form">

<p class="form-row">

<label class="form-label" for="contact-user-name">Name</label>

<input type="text" name="name" id="contact-user-name" class="form-input" placeholder="Enter your name" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row">

<label class="form-label" for="concern">Please choose one of the following:</label>

<option value="I need help with a cat or cats in my neighborhood.">I need help with a cat or cats in my neighborhood.</option> <option value="I need advice, or more information.">I need advice, or more information.</option> <option value="I want to volunteer!">I want to volunteer!</option> </select></p>

<p class="form-row">

If you selected "I want to volunteer!", Please choose one of the following:

<input type="radio" id="1" name="demo-priority"> <label for="1">I want to foster.</label>

<input type="radio" id="2" name="demo-priority" checked> <label for="2">I want to trap.</label>

<input type="radio" id="3" name="demo-priority"> <label for="3">I can transport cats to/from clinics.</label>

<input type="radio" id="4" name="demo-priority"> <label for="4">I'd like to help in other ways.</label>

</p>

<p class="form-row"> <label class="form-label" for="contact-user-phone">Phone Number</label> <input type="phone" name="phone" id="contact-user-phone" class="form-input" placeholder="Enter your phone number" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-user-email">Email</label> <input type="email" name="email" id="contact-user-email" class="form-input" placeholder="Enter your email address" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-message">Message</label>

<p>Please give as much detail as possible when requesting help, such as the number of cats/kittens in need, if any are pregnant or injured, and any challenges you suspect may have an impact on trapping.</p>

 <textarea name="message" id="contact-message" class="form-textarea" rows="5" placeholder="Enter your message"></textarea> <span class="input-focus" aria-hidden="true" required></span> </p>

<input type="hidden" name="form-name" value="contactForm" /> <p class="form-row form-submit">

<button type="submit" class="primary button">Send Message</button> </p> </form>