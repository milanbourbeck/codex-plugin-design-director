---
name: brief
description: Design brief and visual direction before frontend implementation.
---

# brief

Use when the user wants a strong visual direction before building or redesigning a frontend. Use for landing pages, SaaS products, dashboards, portfolios, one-pagers, and product websites. Produces a design brief, style direction, UX intent, and implementation guidance before code changes.

## Handle Migration

Canonical skill handle: `$brief`. Legacy internal name: `creative-direction-brief -> brief`.

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

1. Understand the page or app goal, target audience, product promise, and conversion goal.
2. Audit existing assets, content, screenshots, visual references, and technical constraints when available.
3. Propose 2-3 possible design directions, then give one clear recommendation.
4. Describe each direction through mood, typography, color character, layout rhythm, imagery, component style, motion style, CTA strategy, accessibility impact, and implementation difficulty.
5. Explicitly reject generic AI-SaaS patterns when they do not serve the product.
6. Produce a design brief and implementation guidance.
7. Do not edit code unless the user asks for implementation.
