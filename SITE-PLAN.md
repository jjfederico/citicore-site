# Citicore Properties — Site Plan

## Status
First-pass HOMEPAGE only (index.html). Nav links are in-page anchors standing in for future pages.

## Homepage order
Header · Hero · Proof bar (Straightforward / Direct / Discreet / Local) · The Firm · Acquisition Criteria (summary) · Platform pillars · Projects (Owned / Sold) + West 4th before/after · Grove brokerage · Team · Why sell to us · Deal submission form · Off Grid (compact) · Footer

## Brand
- Palette "Grey & Blue": Slate #1A2430 (dark sections, text), White #FFFFFF, Mist #F2F4F7, Line #D8DEE5, Grey #66707C, Blue accent #2E6096 (hover #234C78, on-dark #9DBDE0) for buttons, section labels and Owned status. Rejected so far: navy/gold, brick, green, warm grey/taupe.
- Logo: 2B "Front Door" wordmark (inline, Archivo wide).
- Tailwind tokens still named `navy`/`brass`/`green` but map to the cool greys — rename when the site is componentized.

## Content rules (from John)
- No volume stats, AUM, deal counts, buy range or testimonials.
- Street names only, no house numbers. Projects grouped by street + status to stay distinct.
- First names only on the team. All inquiries route to john@citicoreprops.com · (781) 670-5993.
- No BPA mention — "in-house management".
- Summit is not mentioned anywhere.

## Deferred to future pages
- Acquisitions: full buy box, process, broker policy, full intake form.
- Asset & Property Management page.
- Projects page: full filterable grid, per-project detail, more photos (651 E 7th / N St pending info).
- Brokerage (Grove) page, Team page, Contact page, Vacation Rental page.

## Production hygiene (before launch)
- Form: set `data-endpoint` on #dealForm (Formspree or hub endpoint). Until then it shows "Preview mode".
- Off Grid booking URL is temporary (offgrid-dennis.tiiny.site).
- Tailwind is loaded from the play CDN — fine for the draft; compile CSS for production.
- Hosting: move off Squarespace (static host) and point citicoreprops.com DNS.
- Photos: 595 E 5th closes Tuesday — move to Sold after closing.
