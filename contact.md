---
layout: page
title: Contact Savir
permalink: /projects/

toc: true
toc_label: Contact
---

## Get in Touch

Feel free to reach out to Savir using the contact information below. I'd love to hear from you!

### Contact Details

- **Email:** [savirsinghwork@gmail.com](mailto:savirsinghwork@gmail.com)
- **Twitter:** @kopichiki
- **Discord:** @savirs

### Contact Form

If you prefer, you can also use the contact form below to send me a message directly. I will respond to you via email.

```liquid
{% raw %}
<form action="https://thatformworks.pythonanywhere.com/mailsavir" method="POST">
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" name="address" id="email" required>
  </div>

  <div class="form-group">
    <label for="message">Message:</label>
    <textarea name="important" id="message" rows="5" required></textarea>
  </div>

  <div class="form-group">
    <button type="submit" class="btn btn--primary">Send Message</button>
  </div>
</form>
{% endraw %}
