---
name: design-md
description: Create or update a DESIGN.md source of truth for Codex frontend work.
---

# design-md

Use when the user wants a DESIGN.md or design system source of truth for Codex-driven frontend work. Creates tokens, components, layout rules, motion rules, accessibility rules, and UI decision rules.

## Handle Migration

Canonical skill handle: `$design-md`. Legacy internal name: `generate-design-system-md -> design-md`.

## Operating Rules

- First understand the product goal, audience, content, brand constraints, and desired user action.
- Do not install dependencies. This plugin thinks, structures, evaluates, and prepares design decisions.
- Do not copy Anthropic, Claude, or any specific competitor aesthetic.
- Avoid generic AI-SaaS defaults: blue/purple gradients, interchangeable cards, fake dashboards, stock-feeling hero layouts, and decorative clutter.
- Respect existing project architecture, content, design tokens, and implementation constraints.
- Prefer a clear recommendation over a menu of equally weighted options.
- Treat accessibility, responsiveness, motion restraint, and performance as design constraints from the start.
- Do not change code unless the user explicitly asks for implementation.
- When implementation is requested, coordinate with installed implementation plugins such as `premium-html-uiux` or `design-system-builder`.
- End with changed or proposed files, checks run, remaining risks, and next implementation steps.


## Workflow

1. Inspect existing styles, components, content model, framework, CSS approach, and project conventions.
2. Create or update `DESIGN.md` as a practical source of truth for Codex work.
3. Define tokens for color roles, typography scale, spacing scale, radius, shadows, borders, motion, and breakpoints.
4. Define component rules for buttons, forms, cards, navigation, modals, feature sections, testimonials, pricing, FAQ, and footer.
5. Add rules for when not to animate, responsive behavior, accessibility, and implementation tradeoffs.
6. Preserve existing architecture and avoid introducing dependencies.
7. If code changes are requested later, hand off implementation guidance to the appropriate implementation plugin.
