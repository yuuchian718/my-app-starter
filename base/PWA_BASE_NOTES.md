# PWA Base Notes

## Goal
Document the reusable PWA base setup for future web app projects.

## Reusable base parts
- `vite-plugin-pwa` basic manifest setup
- favicon / apple-touch-icon references in `index.html`
- icon file placement under `public/`
- service worker cache list consistency
- PWA icon verification flow

## Required icon files
- `public/icons/icon-192.png`
- `public/icons/icon-512.png`
- `public/favicon-16x16.png`
- `public/favicon-32x32.png`
- `public/apple-touch-icon.png`
- `public/favicon.ico`

## Important rule
Do not treat business UI or app-specific logic as part of the PWA base.

## Not part of this base
- timer logic
- app-specific screens
- audio logic
- product-specific branding text

## Future usage
For a new project:
1. copy the base structure
2. replace app name, icon assets, and product metadata
3. keep PWA paths consistent
4. verify using the checklist
