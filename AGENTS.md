# Design Director Agent Instructions

## Repository Focus

- Maintain the @dd plugin for creative direction, design briefs, DESIGN.md quality, visual composition, product storytelling, and anti-generic UI standards.
- Design before code. This plugin should think, structure, evaluate, and prepare design decisions.
- Do not install dependencies from this plugin.
- Do not turn design direction skills into implementation skills.

## Quality Priorities

- Briefs should clarify product goal, audience, conversion intent, visual direction, constraints, and implementation guidance.
- DESIGN.md output should be usable as a source of truth for future Codex work.
- Composition guidance should improve hierarchy, section rhythm, CTA placement, and responsive flow.
- Storytelling guidance should improve messaging before visual decoration.
- Polish guidance should remove generic AI-looking UI without adding unnecessary motion.

## Validation

- Keep .codex-plugin/plugin.json valid with canonical handle @dd.
- Keep skill folders and frontmatter names aligned: $brief, $design-md, $compose, $polish, $story.
- Run scripts/validate-plugin.mjs when possible.
