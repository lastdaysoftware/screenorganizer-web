# Series Organizer+ website

Static website for Series Organizer+ by LastDay Software.

## Pages

- `index.html`
- `privacy.html`
- `account-deletion.html`
- `support.html`

## Brand assets

The site uses the production SVG assets from `iconsAndLogos.zip` wherever practical:

- `assets/brand/series-organizer-plus-full-dark.svg` — homepage hero
- `assets/brand/series-organizer-plus-mark-dark.svg` — header/footer
- `assets/brand/icon_master.svg` — favicon
- PNG variants are retained for social/platform fallback use.

All supplied light/dark, wordmark, mark and monochrome variants are preserved under `assets/brand/`.

## Screenshots

Current app screenshots are under `assets/screenshots/`.

## History

Historical Series Organizer screenshots are under `assets/history/`.

## Publication checklist still open

Before Google Play / OAuth publication:

1. Complete and test the authenticated in-app account-deletion workflow.
2. Confirm the Google Play target-audience selections match the published children wording.
3. Add an approved TMDB logo alongside the required attribution notice.
4. Production domain: `https://seriesorganizer.com`. Keep the existing `workers.dev` address available temporarily during migration verification.
5. Verify `privacy.html`, `support.html`, and `account-deletion.html` open directly after deployment.

The site remains static and contains no cookies, analytics, forms, or JavaScript.


## Production deployment

- Canonical production URL: `https://seriesorganizer.com`
- `www.seriesorganizer.com` should permanently redirect to the equivalent apex-domain path while preserving query strings.
- The existing `seriesorganizer-web.lastdaysoftware.workers.dev` address may remain available temporarily during migration verification.
- Cloudflare Worker custom-domain, DNS, redirect, and certificate changes are managed outside this repository and must be verified separately.
