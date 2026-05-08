# Design Director

## Purpose

Design Director gives Codex a stronger design-direction workflow before implementation. It helps define visual direction, product narrative, DESIGN.md systems, UI composition, and final polish without installing dependencies.

## Included Skills

- `creative-direction-brief`
- `generate-design-system-md`
- `premium-ui-composition`
- `visual-polish-pass`
- `product-storytelling-ux`

## When To Use

- Before building or redesigning a landing page, SaaS UI, dashboard, portfolio, agency site, product page, one-pager, or prototype.
- When the product needs a clear visual direction before code.
- When Codex should create a `DESIGN.md` source of truth.
- When an existing UI feels generic and needs premium polish.
- When conversion, messaging, and product storytelling need structure.

## When Not To Use

- Do not use for dependency installation.
- Do not use for direct implementation unless the user explicitly asks for it.
- Do not use to copy Anthropic, Claude, or any competitor's visual style.
- Do not use when a small code fix is all that is needed.

## Installation

Install this plugin from the Premium Codex Workflows marketplace.

Repository: `https://github.com/milanbourbeck/codex-plugin-design-director.git`

## Example Prompts

- `@design-director erstelle mir zuerst eine starke visuelle Richtung für dieses Projekt. Noch keinen Code ändern.`
- `$creative-direction-brief analysiere mein Produkt und erstelle 3 mögliche Designrichtungen mit einer klaren Empfehlung.`
- `$generate-design-system-md erstelle eine DESIGN.md als visuelle und technische Grundlage für Codex.`
- `$premium-ui-composition überarbeite die Seitenstruktur mit Fokus auf Hero, CTA, Trust, Features, Pricing und FAQ.`
- `$visual-polish-pass entferne generische AI-Optik und bringe die UI auf Premium-Niveau.`
- `$product-storytelling-ux verbessere Messaging, Conversion Flow und Landingpage-Story.`

## Maintenance

- Keep this plugin dependency-free.
- Keep skills focused on direction, structure, evaluation, and design decisions.
- Bump `.codex-plugin/plugin.json` version for meaningful releases.
- Run `node scripts/validate-plugin.mjs` before pushing.
