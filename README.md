# Easy Money Lending — Website & Admin

This project contains two responsive site variants and a basic admin dashboard for managing leads.

Variants:
- Variant A: Single-page landing at `/variant-a`
- Variant B: Multi-page site at `/variant-b` (Home, About, Services, Apply, FAQ, Contact)
- Admin: `/admin/index.html` (login required)

Setup:
1. Copy `.env.example` to `.env` and fill values (SMTP, reCAPTCHA, GTM/GA, admin credentials).
2. Place the provided logo image at `public/assets/logo.png`.
3. Install dependencies: `npm install`
4. Start locally: `npm start` then open `http://localhost:3000/variant-a` or `/variant-b`.

Updating contact info:
- Edit `.env` values: `CONTACT_PHONE`, `CONTACT_EMAIL`, `ADDRESS_LINE`.

Lead notifications:
- Email via Nodemailer (configure SMTP in `.env`).
- Optional WhatsApp/SMS via Twilio (configure `TWILIO_*` in `.env`).

Security:
- Deploy behind HTTPS.
- Set strong `ADMIN_PASSWORD`.

