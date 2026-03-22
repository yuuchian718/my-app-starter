# pwa-icon

## Purpose
This module is the reusable entry point for handling PWA icon setup in a new project.

It is intended to help with:
- app icon replacement
- icon file naming consistency
- manifest icon integration
- favicon and apple touch icon checks
- quick verification before release

## Use this module when
Use this module when a new app needs PWA icon setup or when an existing app needs its icon assets replaced or verified.

## Main starter assets used by this module
- `docs/PWA_ICON_TEMPLATE.md`
- `docs/PWA_ICON_CHECKLIST.md`
- `base/pwa-files/PWA_ICON_FILE_REPLACEMENTS.md`
- `base/pwa-files/manifest.webmanifest.example`

## Typical workflow
1. Prepare the new app icon assets
2. Replace the required icon files
3. Update manifest icon paths if needed
4. Verify browser tab icon, install icon, and apple touch icon
5. Run the final checklist before release

## What is not part of this module
This module does not include:
- product-specific brand assets
- timer business logic
- trial, license, or referral logic
- app-specific UI behavior

## Notes
This module is a reusable starter entry, not a product asset pack.
