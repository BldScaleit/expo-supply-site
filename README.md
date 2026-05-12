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

- [ ] Prices live (Ives 1gal $10 / 5gal $50, Smell Fabric same, Andwi/Viann 16oz $10 / 24oz $20 / 32oz $30 / 5gal $300)
- [ ] All Buy buttons → WhatsApp message links (wa.me/15617670388) with pre-filled product-specific text
- [ ] Email: beaubrunyvesjoseph@gmail.com (Chef Yves)
- [ ] Phone: 561-767-0388
- [ ] Hook contact form to Formspree / GoHighLevel (currently `alert()` on submit)
- [ ] Swap chef-section image with a real photo of Chef Yves Beaubrun
