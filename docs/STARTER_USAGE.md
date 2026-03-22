# Starter Usage

## Goal
This repository stores reusable starter assets for future web app projects.

## Structure
- `base/` reusable project foundation
- `modules/` optional modules to enable only when needed
- `docs/` implementation notes and checklists
- `prompts/` Codex prompt templates

## Reuse rules
- Reuse common patterns only once
- Do not duplicate universal docs for every project
- Only create project-specific notes when a project differs from the common pattern

## Current reusable parts
- PWA icon template
- PWA icon troubleshooting checklist
- PWA base setup notes
- Codex prompt for applying the PWA base

## How to use in a new project
1. Start from the base layer
2. Copy only the modules needed for the new project
3. Replace project name, icon assets, metadata, and product-specific content
4. Do not blindly copy unrelated business logic

## Example
If a new project only needs PWA support:
- use `base/`
- use PWA docs
- do not add unrelated modules

If a new project needs trial but not language switching:
- use `base/`
- enable `modules/trial-system/`
- do not enable `modules/ui-language-switch/`
