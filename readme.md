# Fermyon Email Templates

These are responsive, platform agnostic templates for Fermyon emails - based off of the [Responsive HTML Email Template](https://github.com/leemunroe/responsive-html-email-template) by [@leemunroe](https://github.com/leemunroe).

* Transactional Emails
* Conversational Emails
* Newsletter Emails


## Usage in Messaging Platforms

Different tools like Mailchimp, Hubspot, Mailgun, Sendgrid, Intercom etc have their own formatting snippets to embed things like usernames, links and editable content. These templates can theoretically be used in any of those messaging platforms, but will require template tweaks to integrate into how they render, edit and send their emails.

Consult their documentation, and always remember to [inline the CSS](https://htmlemail.io/inline/) when working with these templates. Email is notorious for inconsistent CSS support across different devices and clients (Gmail/Outlook/etc) so make sure to double-check everything and **test send** before publishing your content!


## Images in email

When inserting images remember to include the following attributes or risk them breaking in different clients:

* `src`
* `alt`
* `width`
* `height`
* `border`

Example:

`<img src="https://absolute-path-to-image.jpg" alt="Useful alt text" width="500" height="300" border="0" style="border:0; outline:none; text-decoration:none; display:block;">`

[More information here](https://www.smashingmagazine.com/2017/01/introduction-building-sending-html-email-for-web-developers/)
