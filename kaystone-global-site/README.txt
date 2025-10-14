# Kaystone Global — One‑Page Site

This folder contains a production‑ready one‑page site for **Kaystone Global** with bilingual EN/TR content, Tailwind styling, lead magnet form, Calendly section, and legal pages.

## Files
- `index.html` — main site
- `privacy.html`, `terms.html` — legal placeholders
- `assets/` — favicon + OG image placeholders

## Quick Deploy
### Option A: Vercel / Netlify (static hosting)
1. Upload this folder as a new project.
2. Set the site domain (e.g., `kaystoneglobal.com` or `kaystone.co.uk/global`).
3. Done.

### Option B: cPanel / Any static host
Upload the folder contents to your web root (or a subdirectory).

## Connect the Forms
- Replace both `https://formspree.io/f/your-id` URLs with your Formspree endpoint (or HubSpot/ConvertKit forms).
- For WhatsApp, update `https://wa.me/44` to your full number (e.g., `https://wa.me/447700000000`).

## Calendly Embed
Replace the "Embed your Calendly here" block with the inline embed code from Calendly:
```html
<div class="calendly-inline-widget" data-url="https://calendly.com/YOUR-SLUG/intro-call" style="min-width:320px;height:700px;"></div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
```

## SEO
- Update `og:image`, `favicon`, and the Organization `logo` URL in the `<head>` of `index.html`.
- Add your Google Analytics (GA4) snippet before `</body>` if required.

## Notes
- Colors: Navy `#0B2B4C`, Gold `#C6A667`.
- Typography is system default via Tailwind CDN.
- Bilingual toggle switches all elements carrying `data-en` / `data-tr` attributes.

