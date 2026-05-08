---
name: polish
description: Remove generic AI-looking UI and apply a premium visual polish pass.
---

# polish

Use when the user wants a final premium polish pass to remove generic AI-looking UI, improve spacing, typography, color balance, microinteractions, responsiveness, and visual consistency.

## Handle Migration

Canonical skill handle: `$polish`. Legacy internal name: `visual-polish-pass -> polish`.

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

1. Review the UI for generic AI patterns: interchangeable gradient heroes, too many rounded cards, weak typography, dull icon grids, equal sections, artificial testimonials, excessive shadows, and poor mobile hierarchy.
2. Improve typography, spacing, CTA contrast, section differentiation, and component consistency.
3. Use subtle microinteractions only when they clarify affordance, feedback, or state.
4. Do not add unnecessary animation. Respect `prefers-reduced-motion`.
5. Keep performance and accessibility intact.
6. Provide a visual review summary covering what felt generic, what changed, risks, and remaining opportunities.
