# Abdul Rehman — Shopify Portfolio

A responsive, editorial portfolio with three original concept case studies and an interactive product-page demonstration. Plain HTML, CSS, and JavaScript. No installation or build required.

## Deploy to Vercel in minutes

1. Unzip this package.
2. Create a new repository on GitHub.
3. Upload **the files inside `shopify-portfolio`** to the repository root. `index.html` must be at the root, not inside an extra folder.
4. In Vercel, choose Add New → Project and import that repository.
5. Choose Framework Preset **Other**. Leave Build Command empty and Output Directory as the root/default. Deploy.
6. Share the resulting Vercel URL.

## Preview locally

Open `index.html` in a browser. For a local server, run `python -m http.server 3000` in this folder, then visit http://localhost:3000.

## Personalize before sharing

- Edit name, introduction, services, and about text in `index.html` to reflect your actual experience. Draft skills and service descriptions should be checked for accuracy.
- Contact currently opens a copyable project brief. It does not send a message. Replace the contact button with your real email or booking link when ready; no unverified email has been invented.
- Project details are in the `projects` object in `app.js`.
- Replace concepts with your own authorized projects and real project links when available. Do not remove concept disclosures unless the content is replaced with verified work.
- No client logos, testimonials, revenue claims, or past results are invented.

## What works

Responsive layouts, accessible project dialogs, finish selection, size-dependent demo pricing, quantity validation, demo-bag feedback, care/delivery accordions, and a copyable project brief.

## Scope

This is a portfolio website, **not an installable Shopify theme**. The product experience is a front-end demonstration with no Shopify API, checkout, payment processing, order fulfillment, backend form, or analytics. Demo bag state resets on refresh. All products and brands are fictional. Product illustrations are original CSS artwork; there are no third-party store screenshots or copied client projects. Google Fonts are loaded externally, with local font fallbacks if unavailable.

## Research references

The product-demo structure is informed by Shopify's official documentation on product media, variants, and add-to-cart forms:
https://shopify.dev/docs/storefronts/themes/architecture/templates/product/overview

Related-product reference for future connected-store work:
https://shopify.dev/docs/storefronts/themes/product-merchandising/recommendations/related-products

These references do not imply Shopify endorsement or a working Shopify integration.

## Files

- `index.html`: all portfolio sections and product demo
- `style.css`: responsive design and original CSS product illustrations
- `app.js`: project dialogs and interactive demo
- `vercel.json`: static hosting settings

No API keys, environment variables, or paid dependencies required.
