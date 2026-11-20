# Verification — 2026-11-20

- 14 HTML pages: all local links, fragments and assets pass static resolution checks.
- Ten unique business names/slugs/phone numbers. Repository metadata and relevant source identity audit recorded in research.json.
- Browser tested at 1440×1000 and 390×844: no horizontal overflow, no broken loaded images, no JavaScript exceptions.
- All ten: mobile menu opens/closes with Escape; gallery dialog opens/closes; occasion preset updates form; generated WhatsApp URI retains Arabic, ampersand and heart characters; past dates rejected.
- axe-core 4.10.3 WCAG 2 A/AA and 2.1 AA: one contrast finding in Naseem form note corrected, then rechecked with no violations. Other nine initially had no violations.
- Additional shared form test: whitespace-only name rejected, valid name accepted.
- Screenshots visually reviewed at desktop and mobile; five layout variants and ten palettes.

Limitations: automated accessibility scans are not full accessibility certification. No real messages, orders or payments were sent. Published telephone listings and WhatsApp links are not live confirmation of ownership or availability. No claim of zero possible defects. Business website absence and previous-work checks are limited to the recorded sources/scope.

## Deployment verification

GitHub Pages run 44795449139 succeeded. All 38 published HTML/CSS/JS/image/font/icon files returned HTTP 200 and matched the local file SHA-256. All ten pages also passed a 360px overflow check.
