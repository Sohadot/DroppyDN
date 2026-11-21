# DroppyDN.com — Acquisition landing page

A lightweight, static, concept-first landing page for **DroppyDN.com**. The domain itself is the asset being offered. The site does not claim to operate a domain marketplace, intelligence platform, or drop-catching service.

## Structure

- `index.html`: semantic landing page, direct Afternic acquisition CTAs, canonical/OG/Twitter metadata, and JSON-LD.
- `styles.css`: responsive, dependency-free visual system.
- `assets/hero-water.webp`: owner-provided liquid/water background image, optimized for the hero.
- `assets/og-droppydn.jpg`: 1200×630 social-sharing graphic based on the generated approved artwork.
- `assets/favicon.svg`: simple brand mark.
- `robots.txt`, `sitemap.xml`: indexing fundamentals.
- `_headers`: security and static asset headers for Cloudflare Pages.

## Deployment

Deploy the repository's root as a static Cloudflare Pages project: no build command or framework required. Set the output directory to `/` (repository root). Attach the verified domain `droppydn.com` through Cloudflare custom domains and DNS. Confirm canonical host and HTTPS before enabling broad sharing. GitHub Pages can also serve the static files but does not implement Cloudflare Pages `_headers` semantics.

## Acquisition destination

All purchase CTAs currently point to:

`https://www.afternic.com/forsale/droppydn.com`

**Important:** This is the conventional domain-specific Afternic URL; the live listing's existence, sale status, and checkout flow are **not confirmed**. Verify the destination, seller account, price, and listing availability before activating a public campaign. Replace it in `index.html` if the actual unique Afternic listing URL is different.

## Pre-launch checks

1. Confirm both hero and OG assets return `200` and correct MIME types on the live domain.
2. Inspect the `og:image` response in social debuggers (Facebook Sharing Debugger and LinkedIn Post Inspector), especially after cache changes.
3. Verify all acquisition buttons resolve to the correct authorized Afternic listing.
4. Verify canonical, robots, sitemap, mobile viewport, keyboard accessibility, and responsive behavior on the deployed origin.
5. Perform trademark due diligence and confirm asset-scope wording before marketing.

No revenue, product operation, or trademark ownership is implied by this design.
