---
title: "Contact me"
template: "page"
---

<form name="contact" method="POST" netlify-honeypot="bot-field"
data-netlify-recaptcha="true" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
