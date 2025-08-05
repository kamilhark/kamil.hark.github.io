---
layout: page
title: Contact Us
permalink: /contact/
custom_css: custom.css
---

# Get in Touch

Have questions about our roof box rentals? Need to make a reservation? We're here to help!

## Contact Information

<div class="contact-info">
  <div class="contact-item">
    <i class="icon-location"></i>
    <h3>Visit Our Showroom</h3>
    <p>{{ site.address }}</p>
    <p><strong>Hours:</strong><br>
    Monday-Friday: 9am-6pm<br>
    Saturday: 10am-4pm<br>
    Sunday: Closed</p>
  </div>
  
  <div class="contact-item">
    <i class="icon-phone"></i>
    <h3>Call Us</h3>
    <p>{{ site.phone }}</p>
    <p>We're available during business hours to answer your calls.</p>
  </div>
  
  <div class="contact-item">
    <i class="icon-email"></i>
    <h3>Email Us</h3>
    <p><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
    <p>We typically respond to emails within 24 hours.</p>
  </div>
</div>

## Reservation Form

<div class="contact-form">
  <form action="#" method="POST" id="contact-form">
    <div class="form-group">
      <label for="name">Full Name*</label>
      <input type="text" id="name" name="name" required>
    </div>
    
    <div class="form-group">
      <label for="email">Email Address*</label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div class="form-group">
      <label for="phone">Phone Number*</label>
      <input type="tel" id="phone" name="phone" required>
    </div>
    
    <div class="form-row">
      <div class="form-group half">
        <label for="pickup-date">Pickup Date*</label>
        <input type="date" id="pickup-date" name="pickup-date" required>
      </div>
      
      <div class="form-group half">
        <label for="return-date">Return Date*</label>
        <input type="date" id="return-date" name="return-date" required>
      </div>
    </div>
    
    <div class="form-group">
      <label for="product">Roof Box Model*</label>
      <select id="product" name="product" required>
        <option value="">-- Select a Roof Box --</option>
        <optgroup label="Compact Series">
          <option value="compact-traveler">Compact Traveler</option>
          <option value="urban-glider">Urban Glider</option>
        </optgroup>
        <optgroup label="Family Series">
          <option value="family-explorer">Family Explorer</option>
          <option value="vacation-master">Vacation Master</option>
        </optgroup>
        <optgroup label="Premium Series">
          <option value="premium-adventure">Premium Adventure</option>
          <option value="elite-voyager">Elite Voyager</option>
        </optgroup>
      </select>
    </div>
    
    <div class="form-group">
      <label for="accessories">Accessories (Optional)</label>
      <div class="checkbox-group">
        <label>
          <input type="checkbox" name="accessories" value="roof-rack"> Universal Roof Rack System
        </label>
        <label>
          <input type="checkbox" name="accessories" value="crossbars"> Premium Crossbars
        </label>
        <label>
          <input type="checkbox" name="accessories" value="cargo-net"> Interior Cargo Net
        </label>
      </div>
    </div>
    
    <div class="form-group">
      <label for="vehicle">Vehicle Make and Model*</label>
      <input type="text" id="vehicle" name="vehicle" placeholder="e.g., Toyota RAV4 2023" required>
    </div>
    
    <div class="form-group">
      <label for="message">Additional Information</label>
      <textarea id="message" name="message" rows="4" placeholder="Tell us about any special requirements or questions you have."></textarea>
    </div>
    
    <div class="form-group">
      <label class="checkbox-container">
        <input type="checkbox" name="terms" required>
        I agree to the <a href="/terms">rental terms and conditions</a>*
      </label>
    </div>
    
    <div class="form-actions">
      <button type="submit" class="button primary-button">Submit Reservation Request</button>
    </div>
  </form>
</div>

## Frequently Asked Questions

<div class="faq-section">
  <div class="faq-item">
    <h3>How do I install the roof box on my car?</h3>
    <p>We offer professional installation services with every rental. If you prefer to install it yourself, we'll provide detailed instructions and can demonstrate the process when you pick up the box.</p>
  </div>
  
  <div class="faq-item">
    <h3>What if I don't have roof rails on my car?</h3>
    <p>We offer universal roof rack systems that can be installed on most vehicles, even those without factory roof rails. Please mention your vehicle type when making a reservation so we can ensure compatibility.</p>
  </div>
  
  <div class="faq-item">
    <h3>How much weight can a roof box hold?</h3>
    <p>Weight capacity varies by model, but most of our roof boxes can hold between 50-75kg (110-165lbs). The specific weight limit for each model is listed on the product page and will be provided with your rental.</p>
  </div>
  
  <div class="faq-item">
    <h3>Can I extend my rental period?</h3>
    <p>Yes, subject to availability. Please contact us as soon as possible if you need to extend your rental period. Late returns without prior arrangement may incur additional fees.</p>
  </div>
  
  <div class="faq-item">
    <h3>What is the security deposit amount?</h3>
    <p>The security deposit varies depending on the roof box model, typically ranging from $100-$300. The deposit is fully refundable upon return of the equipment in good condition.</p>
  </div>
</div>

## Location Map

<div class="map-container">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3000!2d-73.9857!3d40.7484!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNDDCsDQ0JzU0LjIiTiA3M8KwNTknMDguNSJX!5e0!3m2!1sen!2sus!4v1628000000000!5m2!1sen!2sus" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</div>