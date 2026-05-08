# Design Director

## Purpose

Design direction, design briefs, DESIGN.md systems, UI composition, product storytelling, and premium polish planning before implementation.

## Included Skills

- `$brief`
- `$design-md`
- `$compose`
- `$polish`
- `$story`

## Quick Commands

- @dd $brief — create visual direction first
- @dd $design-md — create or update DESIGN.md
- @dd $compose — improve page composition and hierarchy
- @dd $polish — remove generic AI-looking UI
- @dd $story — improve product storytelling and conversion

## When To Use

- Use `@dd` when you want this plugin's focused workflow.
- Use the short skill handles with `$` for explicit control.
- Use implicit selection when the request matches a skill description.

## When Not To Use

- Do not use this plugin outside its focused domain.
- Do not rely on keywords as invocation aliases.
- Do not add dependencies unless the underlying skill explicitly supports implementation and the project needs them.

## Installation

Install this plugin from the Premium Codex Workflows marketplace.

Repository: `https://github.com/milanbourbeck/codex-plugin-design-director.git`

## Example Prompts

1. `@dd $brief Create a strong visual direction for this landing page. Do not edit code yet.`
2. `@dd $design-md Create a DESIGN.md source of truth for this project.`
3. `@ui $stack Integrate the premium Vanilla HTML UI/UX stack. Install only what is actually needed.`
4. `@ui $modernize Improve this existing HTML/CSS/JS UI with better hierarchy, responsiveness, semantics, and focus states.`
5. `@qa $visual Test this frontend in desktop, tablet, and mobile viewports. Document issues and fix the most important ones.`
6. `@qa $a11y Improve keyboard navigation, focus states, forms, dialogs, labels, and reduced-motion behavior.`
7. `@qa $perf Find bundle, image, layout shift, font, and animation performance issues. Fix what is safe.`
8. `@ship $e2e Take this frontend task from analysis to implementation, QA, polish, and PR-ready delivery.`

## Migration Note

- Old plugin repository names may stay unchanged.
- New Codex plugin handle: `@dd`.
- New skill handles use `$`.
- `creative-direction-brief` is now `$brief`
- `generate-design-system-md` is now `$design-md`
- `premium-ui-composition` is now `$compose`
- `visual-polish-pass` is now `$polish`
- `product-storytelling-ux` is now `$story`
- If Codex does not show updates immediately, restart or reload Codex and reinstall or refresh the marketplace.

## Maintenance

- Keep the plugin `name` field as the canonical handle.
- Keep each skill folder name and frontmatter `name` in sync.
- Bump `.codex-plugin/plugin.json` version for meaningful releases.
- Run `node scripts/validate-plugin.mjs` before pushing.
