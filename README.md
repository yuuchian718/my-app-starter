# my-app-starter

A reusable starter kit for future web app projects.

## What this repository is for
This repository stores reusable project assets so future apps do not need to rebuild the same foundations again.

It is designed as:

- `base/` = shared foundation
- `modules/` = optional modules enabled only when needed
- `docs/` = reusable implementation notes and checklists
- `prompts/` = reusable Codex prompt templates

## Current reusable assets
- PWA icon template
- PWA icon troubleshooting checklist
- PWA base notes
- Starter usage guide
- Template config
- Codex prompt for applying the PWA base

## Reuse principle
Do not blindly copy a whole product project.

Use this repository by:
1. starting from the base layer
2. enabling only the modules needed
3. replacing app name, icon assets, metadata, theme, and product-specific content
4. avoiding unrelated business logic

## Current status
The PWA base layer is the first reusable part that has already been validated.

## Planned next modules
- trial-system
- ui-language-switch
- license-system
- referral-system
- study-timer

## Repository Structure Rules

This repository is a reusable starter for future Web App projects.

The goal is:
- start new projects faster
- reuse stable setup patterns
- avoid rebuilding the same foundation repeatedly
- keep product-specific logic out of the starter

### `base/`
Use `base/` for reusable foundational setup shared by most projects.

Examples:
- PWA base integration
- manifest examples
- service worker base files
- Vite / HTML setup examples
- file replacement guides

Rules:
- must not depend on a specific product
- should be useful in most new projects
- should remain valid even without business logic

### `modules/`
Use `modules/` for optional reusable capabilities.

Examples:
- `pwa-icon`
- future language switch module
- future theme switch module
- future install prompt module

Rules:
- must be optional
- must be reusable across multiple projects
- must have clear boundaries
- must not contain product-specific business logic

### `docs/`
Use `docs/` for instructions, checklists, templates, and troubleshooting notes.

Examples:
- icon templates
- verification checklists
- usage notes
- replacement guides

### `prompts/`
Use `prompts/` for reusable Codex instruction templates.

Rules:
- keep them generic
- keep them reusable
- avoid project-specific prompts unless later generalized

## What should not go into this starter
Do not place product-specific logic here unless it has been clearly generalized.

Examples:
- tomato timer business logic
- trial / license / referral logic
- product-specific UI flows
- product-specific branding assets
- project-private data structures

## Decision rule
Before adding anything to this repository, ask:

1. Can this work outside one specific product?
2. Can this be reused in multiple future apps?
3. Is it a base asset or an optional module?
4. Does it have clear boundaries?
5. Is it already stable enough to reuse?

If the answer is unclear, keep it in the product repo for now.
