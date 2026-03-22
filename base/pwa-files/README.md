# PWA Base Files

These files are reusable reference templates for the PWA base layer.

## Included examples
- `vite.config.pwa-example.ts`
- `index.pwa-links-example.html`
- `sw.pwa-example.js`

## Purpose
These files store the validated PWA base implementation pattern from a working project.

## Reuse rule
Do not blindly copy them into every project as-is.

When reusing:
1. keep only the PWA-related base parts
2. replace app name, metadata, and icon assets
3. do not carry over unrelated business logic
4. verify consistency across manifest, index.html, and service worker

## Not included here
- timer logic
- audio logic
- settings modal
- product-specific UI
