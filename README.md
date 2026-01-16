# I.S.K NightLife Vending Machine

Veteran-owned nightlife vending experience for bars, clubs, and casinos in San Antonio—now implemented as a React single-page site (no build step required).

## Preview
- Serve locally (recommended): `python -m http.server` then open the shown URL.
- Or open `index.html` directly; it imports React via ESM CDN.

## Project structure
- `index.html` — React-powered landing page (hero, why-it-works, product mix, operations loop, gallery, contact CTA).
- `V1.jpeg` — Machine hero shot used in hero and gallery.
- `V2.jpeg` — Packaging/merchandising photo used in gallery.
- `V5.webp` — Device colorways photo used in gallery.

## Customization
- Update the contact email/phone in the CTA to your real details.
- Contact form: replace the `action` URL in `index.html` if you want Formsubmit, Formspree, or Netlify Forms.
- Analytics: update the Plausible `data-domain` value in `index.html` to your live domain.
- Adjust copy in `index.html` to match your offer or compliance language.
- Swap images by replacing the files or updating the `gallery` array in the script.

## Compliance note
- Positioned for adult (21+) venues. Ensure age verification, applicable federal/state/local rules, and product restrictions are met before deploying.
