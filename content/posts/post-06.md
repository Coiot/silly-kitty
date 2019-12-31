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

<form name="shirtForm" method="POST" netlify-honeypot="bot-field" data-netlify="true" id="shirt-form" class="shirt-form">

<p class="form-row">

<label class="form-label" for="shirt-name">Name</label>

<input type="text" name="name" id="shirt-name" class="form-input" placeholder="Enter your name" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="shirt-phone">Phone Number</label> <input type="phone" name="phone" id="shirt-phone" class="form-input" placeholder="Enter your phone number" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="shirt-email">Email</label> <input type="email" name="email" id="shirt-email" class="form-input" placeholder="Enter your email address" required> <span class="input-focus" aria-hidden="true"></span> </p>

<p class="form-row"> <label class="form-label" for="shirt-address">Address</label>

<input type="text" name="name" id="shirt-address" class="form-input" placeholder="Enter your name" required>  <span class="input-focus" aria-hidden="true" required></span> </p>

<p class="form-row">

<label class="form-label" for="size">Choose Size</label>

<select name="size" id="size">

<option value="Small">S</option> <option value="Medium">M</option> <option value="Large">L</option>  <option value="Extra Large">XL</option> </select></p>

<label class="form-label" for="color">Choose Color</label>

<select name="color" id="color">

<option value="Burgundy/Red">Burgundy/Red</option> <option value="Purple">Purple</option> <option value="Turquoise">Turquoise</option> </select></p>

<p class="form-row" id="contact-radio">

<p><label for="shipping">Shipping or Pickup?</label></p><input type="radio" id="1" name="shipping" value="Please ship my order!"> <label for="1">Please ship my order!</label><input type="radio" id="2" name="shipping" value="I'd like to pick up my order."> <label for="2">I'd like to pick up my order.</label>

</p>

<p class="form-row"> <label class="form-label" for="shirt-message">Message</label>

<p>Comment or Message - If you'd like to order more than one t-shirt, please specify the details (Size, Color, and Quantity) for your FULL order below.</p>

 <textarea name="message" id="shirt-message" class="form-textarea" rows="4" placeholder="Enter your message" required></textarea> <span class="input-focus" aria-hidden="true" required></span> </p>

<input type="hidden" name="form-name" value="contactForm" /> <p class="form-row form-submit">

<button type="submit" class="primary button">Send Message</button> </p> </form>