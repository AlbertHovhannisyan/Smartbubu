# Smart Bubu

Landing page for **Smart Bubu — HR Consulting by Anna**: HR solutions for modern teams.

A plain static site (no build step): `index.html`, `tokens.css` (brand colours, spacing, radii), `booking-config.js` (the booking link), `images/` (WebP), `robots.txt` and `sitemap.xml`.

## Before going live
- **Booking link:** open `booking-config.js` and paste the booking page link (Calendly, Cal.com, Google Calendar, Microsoft Bookings…). Every Book button on the site uses it.
- Replace `[Anna's background…]` and `[Anna's email]` / `mailto:[ANNA@EMAIL]` with real details.

## SEO
- Title, description, canonical URL (`https://smartbubu.com/`), Open Graph / Twitter share preview (`images/og-image.png`) and schema.org business data are in the `<head>` of `index.html`.
- `robots.txt` and `sitemap.xml` point search engines at `https://smartbubu.com/`. If the domain changes, update it in those two files and in `index.html`.
- After going live, add the site in Google Search Console and submit `https://smartbubu.com/sitemap.xml`.

## Hosting
Works as-is on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), Netlify or Vercel.
