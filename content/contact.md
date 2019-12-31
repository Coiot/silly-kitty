---
title: Contact
subtitle: We're always shifting through phone numbers as our team of volunteers changes,
  so contacting us through email is the best way. You can [email us at our at address](mailto:nwacommunitycatproject@gmail.com)
  or use the form below.
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

<p class="form-row"> <label class="form-label" for="contact-address">Address/Location</label>

<p>If requesting advice or assistance, it is VERY helpful if you include your address (or at least the city/general area). This helps us more quickly determine how best we can help. We do NOT share your private information with anyone without your consent.</p>

<textarea name="address" id="contact-address" class="form-textarea" rows="2" placeholder="Enter your Address or General Location"></textarea> <span class="input-focus" aria-hidden="true" required></span> </p>

<p class="form-row">

<label class="form-label" for="concern">Please choose one of the following:</label>

<select name="concern" id="concern">

<option value="I need help with a cat or cats in my neighborhood.">I need help with a cat or cats in my neighborhood.</option> <option value="I need advice, or more information.">I need advice, or more information.</option> <option value="I want to volunteer!">I want to volunteer!</option> </select></p>

<p class="form-row">

<p class="form-label" name="contact-radio">If you selected "I want to volunteer!", Please choose one of the following:</p><input type="radio" id="1" name="contact-radio" value="N/A"> <label for="1">N/A.</label><input type="radio" id="2" name="contact-radio" value="I want to foster."> <label for="2">I want to foster.</label><input type="radio" id="3" name="contact-radio" value="I want to trap."> <label for="3">I want to trap.</label><input type="radio" id="4" name="contact-radio" value="I want to transport cats to/from clinics."> <label for="4">I can transport cats to/from clinics.</label><input type="radio" id="5" name="contact-radio" value="I'd like to help in other ways."> <label for="5">I'd like to help in other ways.</label>

</p>

<p class="form-row"> <label class="form-label" for="contact-user-phone">Phone Number</label> <input type="phone" name="phone" id="contact-user-phone" class="form-input" placeholder="Enter your phone number" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-user-email">Email</label> <input type="email" name="email" id="contact-user-email" class="form-input" placeholder="Enter your email address"> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-message">Message</label>

<p>Please give as much detail as possible when requesting help, such as the number of cats/kittens in need, if any are pregnant or injured, and any challenges you suspect may have an impact on trapping.</p>

 <textarea name="message" id="contact-message" class="form-textarea" rows="4" placeholder="Enter your message" required></textarea> <span class="input-focus" aria-hidden="true" required></span> </p>

<input type="hidden" name="form-name" value="contactForm" /> <p class="form-row form-submit">

<button type="submit" class="primary button">Send Message</button> </p> </form>