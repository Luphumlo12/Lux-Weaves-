# Lux Weaves website

A responsive, multi-page startup website for Lux Weaves, a Johannesburg hair-extension studio.

## Pages

- `index.html` — brand landing page
- `shop.html` — dynamically rendered, searchable and sortable product catalogue
- `services.html` — installation and care offerings
- `enquiry.html` — consultation and product enquiry form
- `contact.html` — general-contact form that composes an email to `hello@luxweaves.co.za`

## SEO and responsive design

Every page includes a specific title, meta description, semantic headings, descriptive image alt text, mobile navigation and responsive layouts. The catalogue uses `srcset`/`sizes` for responsive product imagery. `robots.txt` and `sitemap.xml` are included; update the domain in the sitemap and robots file before publishing if the final domain differs.

## Changelog

- 2026-09-18: Built the Lux Weaves multi-page site, shared external stylesheet, responsive layouts and mobile navigation.
- 2026-09-18: Added JavaScript catalogue filtering/sorting, form validation, enquiry feedback and email composition for general contacts.
- 2026-09-18: Added on-page SEO metadata, sitemap and crawler instructions.

## Publishing

Upload all `.html` files plus `style.css`, `script.js`, `robots.txt` and `sitemap.xml` to GitHub Pages, Netlify or a similar static host.
