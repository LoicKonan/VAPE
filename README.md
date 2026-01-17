# PulseVend Nightlife Vending

Veteran-owned nightlife vending experience for bars, clubs, and casinos in San Antonio. This repo is a static single-page site with no build step.

## Highlights
- Static SPA with a single `index.html` entry point.
- Sections: hero, why it works, operations flow, gallery, and contact CTA.
- Ready-to-use photo assets included in the repo.

## Quick start
- Serve locally (recommended): `python -m http.server --directory public` then open the shown URL.
- Or open `public/index.html` directly in a browser.

## Project structure
```
public/
├── assets/          — All images (logo, products, gallery)
├── index.html       — Landing page and all UI/CSS/JS
├── robots.txt       — Search engine directives
└── sitemap.xml      — Sitemap for SEO
```

## Customization
- Update the contact email/phone in the CTA to your real details.
- Contact form: replace the `action` URL in `public/index.html` if you want Formsubmit, Formspree, or Netlify Forms.
- Analytics: update the Plausible `data-domain` value in `public/index.html` to your live domain.
- Adjust copy in `public/index.html` to match your offer or compliance language.
- Swap images by replacing files or updating the `gallery` section in the HTML.

## Gallery
![Machine hero shot](public/assets/V1.jpeg)
![Packaging and merchandising](public/assets/V2.jpeg)
![Device colorways](public/assets/V5.webp)

## Compliance note
- Positioned for adult (21+) venues. Ensure age verification, applicable federal/state/local rules, and product restrictions are met before deploying.
