# Saudi Floral Ten Implementation Plan

Goal: deliver ten tested Arabic florist proposals and publish them to GitHub Pages.
Architecture: generated semantic HTML pages, shared CSS and browser JS, local assets, one new repository with separate shop paths. No server or payment dependencies.
Tech stack: Python build script, vanilla HTML/CSS/JS, local WOFF2 fonts, GitHub Pages.
Spec: docs/design.md. User delegated design and execution; implement natively in this session.

## Constraints
Use verified shop identity and contact, no fabricated business claims. Avoid duplicates in accessible repositories and research data. Keep image inspiration labels and proposal disclosure. Do not send messages to businesses.

## Review focus
- RTL layout at 360px with long Arabic names: no horizontal overflow.
- Empty/past-date inquiries: validation before drafting WhatsApp message.
- Arabic and special characters: URI encode generated messages.
- Modal and mobile menu keyboard flow: Escape and focus restored.
- Published project subpaths: relative assets and navigation work.

## Tasks
- [x] Research candidates and source contact fields in research.json; save excluded matches and audit scope.
- [x] Download illustrative flower images and Arabic fonts to assets; record attribution.
- [x] Build ten pages with custom visual tokens and hero variants, gallery, occasions, inquiry builder and contact section.
- [x] Validate all local links/assets and use real browser at desktop/mobile sizes; fix observed issues.
- [x] Create new GitHub repository, push reviewed source, enable Pages, verify ten deployed pages and deliver index/research/report.
