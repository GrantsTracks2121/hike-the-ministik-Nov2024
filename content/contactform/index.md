---
title: "Contact Hike The Ministik!"
draft: false
summary: "Contact Hike The Ministik!"
showHero: true
heroStyle: "background"
---
<script src="https://www.google.com/recaptcha/enterprise.js" async defer></script>
<form
  id="HikeTheMinistik-contact-form" 
  name="HikeTheMinistik Contact Form" 
  method="POST"
  data-netlify-recaptcha="true"
  data-netlify="true"
>
  <p>
    <label>
      Email: <input type="text" id="name" name="name" />
    </label>
  </p>
  <p>
    <label>
      Message: <textarea id="message" name="message"></textarea>
    </label>
  </p>
  <div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

<form name="contact-test-form" method="POST" data-netlify="true">
  <input type="hidden" name="subject" 
  value="Sales inquiry from mysitename.netlify.app" />
  <p>
    <label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
