# Navkranti deployment

## Files
- `index.html` — main site
- `favicon.svg` — browser favicon
- `og-image.svg` — social preview image
- `qr-navkranti.png` — real QR code pointing to the official Navkranti Google Form
- `robots.txt` — crawler rules
- `sitemap.xml` — sitemap

## Before going live
The custom domain was not supplied. Replace every occurrence of `https://navkranti.in` in:
- `index.html`
- `sitemap.xml`
- `robots.txt`

with your real canonical URL, e.g. `https://www.example.com`.

Then deploy the whole folder to Netlify, Vercel, GitHub Pages, Cloudflare Pages, or another static host.

## DNS
For a custom domain, add the DNS records recommended by your hosting provider. Do not change the Google Form, social URLs, email, or phone unless those details change.
