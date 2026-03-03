# Labless Landing Page

Static single-page landing/whitepaper for:
- https://lab-less.com
- https://labless.bio

## Files
- `index.html`: complete page (HTML + embedded CSS)

## Deploying to both domains
1. Host this `index.html` on any static host (Cloudflare Pages, Netlify, GitHub Pages, S3, etc.).
2. In Squarespace Domains DNS for both domains, point records to the same host.
3. Set `lab-less.com` as primary and 301 redirect `labless.bio` to it (or keep both live with the same content).
