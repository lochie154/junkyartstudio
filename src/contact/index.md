---
layout: default
title: contact
customStyle: >
  :root {
    --main-bg-color:#d9f0e0;
    --main-bg-gradient:radial-gradient(rgb(255, 190, 79),rgb(204, 106, 45));
  }
---

## contact

fill out the form below, or email me at <a href="mailto:junkyartstudio@gmail.com">junkyartstudio@gmail.com</a>.

<form
  name="contact"
  method="POST"
  action="/contact/submitted"
  netlify-honeypot="email-address"
  data-netlify="true"
  >
  <div style="display:none;">
    <label>
      don't fill this out if you are a person:
      <input type="email" name="email-address">
    </label>
  </div>
  <label>
    your email:
    <input type="email" name="email" required>
  </label>
  <label>
    your name:
    <input type="text" name="name" required>
  </label>
  <label>
    your message:
    <textarea name="message" required></textarea>
  </label>
  <label>
    subscribe to my <a href="/newsletter/">snailmail</a>?
    <input type="checkbox" name="mailing-list">
  </label>
  <button type="submit">send</button>
</form>
