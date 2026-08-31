# AI + Facebook Page Growth — Webinar Landing Page

Responsive GitHub Pages landing page with:
- Webinar details
- Registration form
- Name, email, WhatsApp/mobile and Facebook Page/business fields
- Required consent checkbox
- ₹99 Razorpay payment redirect
- Responsive mobile/desktop design

## IMPORTANT: Connect the registration form

The form uses the free FormSubmit service to email registrations to you.

Open `index.html` and find:

```html
<form class="registration-form" action="https://formsubmit.co/YOUR_EMAIL_HERE" method="POST">
```

The registration form is already configured to send submissions to `gns.jyoti@gmail.com`.

No code change is required for the email address.

The form will submit the registration details and then redirect the visitor to:

`https://rzp.io/rzp/HTaatlx`

### First submission
FormSubmit may send a confirmation/activation email to your receiving email address the first time. Complete that activation if requested.

## Publish on GitHub Pages

1. Upload `index.html`, `webinar-poster.png`, and `trainer.png` to the repository root.
2. Go to Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: `main`.
5. Folder: `/ (root)`.
6. Save.

## Important

Do not upload the ZIP file to GitHub Pages. Upload the files inside it directly to the repository root.


Updated agenda includes a Video Optimization topic covering how to choose proper video titles and descriptions.


Payment updated to fixed Razorpay Payment Link: https://rzp.io/rzp/HTaatlx
WhatsApp group CTA added for paid attendees.

## Webinar schedule

- Date: Saturday, 5 September 2026
- Time: 11:00 AM–12:30 PM IST
- Registration: ₹99
- WhatsApp group for attendees who have completed payment: https://chat.whatsapp.com/FFeTniEpK8x73DvfPpZNgP?s=sw&p=i&mlu=4
