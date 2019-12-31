---
title: T-Shirt Order Form
subtitle: 'Support our cause, and look fabulous at the same time! Buy one of our t-shirts. '
excerpt: Support our cause, and look fabulous at the same time! Buy one of our t-shirts.
content_img:
  enabled: false
  path: "/images/IMG_0304-768x1024.jpg"
  url: "#"
  alt: ''
alt_img: "/images/IMG_0304-768x1024.jpg"
sidebar:
  enabled: false
  side: left
date: 2019-12-30T06:00:00.000+00:00
show_in_home_posts: false
show_in_sidebar: true
layout: page
menu:
  footer:
    name: T-Shirts
    weight: 3

---
Just $20 each (*plus shipping, if applicable), these make GREAT gifts!  They also seem to hold up REALLY well to regular laundering, and we absolutely love them!

(*Shipping is via USPS Priority Mail, at a cost of $7.20 / shirt.  If ordering several, we can calculate the most economical shipping charges based on quantity.  If you are willing to pick up your shirt(s) in Fayetteville, then shipping is not applicable)

<form name="contactForm" method="POST" netlify-honeypot="bot-field" data-netlify="true" id="contact-form" class="contact-form">

<p class="form-row">

<label class="form-label" for="contact-user-name">Name</label>

<input type="text" name="name" id="contact-user-name" class="form-input" placeholder="Enter your name" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-user-phone">Phone Number</label> <input type="phone" name="phone" id="contact-user-phone" class="form-input" placeholder="Enter your phone number" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-user-email">Email</label> <input type="email" name="email" id="contact-user-email" class="form-input" placeholder="Enter your email address" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="contact-address">Address</label>

<input type="text" name="name" id="contact-user-name" class="form-input" placeholder="Enter your name" required>  <span class="input-focus" aria-hidden="true" required></span> </p>

<p class="form-row">

<label class="form-label" for="size">Choose Size</label>

<select name="concern" id="size">

<option value="Small">S</option> <option value="Medium">M</option> <option value="Large">L</option>  <option value="Extra Large">XL</option> </select></p>

<label class="form-label" for="color">Choose Color</label>

<select name="concern" id="color">

<option value="Burgundy/Red">Burgundy/Red</option> <option value="Purple">Purple</option> <option value="Turquoise">Turquoise</option> </select></p>

<p class="form-row" id="contact-radio">

<p><label for="contact-radio">If you selected "I want to volunteer!", Please choose one of the following:</label></p><input type="radio" id="1" name="contact-radio" value="N/A"> <label for="1">N/A.</label><input type="radio" id="2" name="contact-radio" value="I want to foster."> <label for="2">I want to foster.</label><input type="radio" id="3" name="contact-radio" value="I want to trap."> <label for="3">I want to trap.</label><input type="radio" id="4" name="contact-radio" value="I want to transport cats to/from clinics."> <label for="4">I can transport cats to/from clinics.</label><input type="radio" id="5" name="contact-radio" value="I'd like to help in other ways."> <label for="5">I'd like to help in other ways.</label>

</p>

<p class="form-row"> <label class="form-label" for="contact-message">Message</label>

<p>Please give as much detail as possible when requesting help, such as the number of cats/kittens in need, if any are pregnant or injured, and any challenges you suspect may have an impact on trapping.</p>

 <textarea name="message" id="contact-message" class="form-textarea" rows="4" placeholder="Enter your message" required></textarea> <span class="input-focus" aria-hidden="true" required></span> </p>

<input type="hidden" name="form-name" value="contactForm" /> <p class="form-row form-submit">

<button type="submit" class="primary button">Send Message</button> </p> </form>