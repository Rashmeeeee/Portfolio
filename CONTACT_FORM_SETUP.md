# 📧 How to Setup Your Contact Form

Your contact form needs to be connected to receive messages at **rashmituladhar70@gmail.com**

## Option 1: Formspree (Easiest & Recommended)

**Formspree** is FREE and easy to set up!

### Steps:

1. Go to **https://formspree.io/**
2. Click "Get Started" (it's free!)
3. Sign up with your email (use rashmituladhar70@gmail.com)
4. Create a new form
5. Copy your form ID (looks like: `xpzgabcd`)
6. Open `index.html` in your editor
7. Find this line (around line 321):
   ```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
8. Replace `YOUR_FORM_ID` with your actual form ID:
   ```html
   <form id="contactForm" action="https://formspree.io/f/xpzgabcd" method="POST">
   ```
9. Save and upload your website!

**Done!** Now when someone fills the form, you'll get an email at rashmituladhar70@gmail.com

---

## Option 2: Netlify Forms (If hosting on Netlify)

If you upload your site to Netlify, it's even easier:

1. Open `index.html`
2. Change the form tag to:
   ```html
   <form id="contactForm" netlify>
   ```
3. Upload to Netlify
4. That's it! Netlify will handle everything

---

## Option 3: Google Forms (Alternative)

1. Create a Google Form
2. Add fields: Name, Email, Message
3. Get the form link
4. Replace the entire form section with an embed code

---

## Current Status

Right now, clicking "Send Message" opens your email client. This works, but Formspree is better because:
- Messages go directly to your inbox
- You get a nice message history
- No email client needed
- Works on mobile

---

## Need Help?

If you have questions, email me or check Formspree's documentation: https://help.formspree.io/

