# Expo Supply International — Static Site

Single-file static site for **Expo Supply International LLC** — Caribbean food + cleaning products distributor based in Lake Worth, FL.

## Tech

- Single `index.html` (Tailwind via CDN, vanilla JS hash routing)
- Fonts: Montserrat + Lato (Google Fonts)
- 5 pages: Home, Products, Product Detail (template), About, Contact
- 4 SKUs with size variant selectors on the 2 cleaning products
- Stripe payment-link placeholders (`https://buy.stripe.com/REPLACE_*`) — swap before going live

## Deploy

Any static host. Just serve the folder root as the site. No build step required.

- **Entry**: `index.html`
- **Assets**: `./images/`

Tested with Kloudbean, deployable to Cloudflare Pages, Netlify, Vercel, GitHub Pages, or plain Nginx.

## Pre-launch checklist

- [ ] Replace `$XX.XX` prices in the `PRODUCTS` object inside `index.html`
- [ ] Replace `https://buy.stripe.com/REPLACE_*` URLs with real Stripe payment links per variant
- [ ] Hook contact form to Formspree / GoHighLevel (currently `alert()` on submit)
- [ ] Swap chef-section image with a real photo of Chef Yves Beaubrun
