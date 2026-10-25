---
name: clean-ui-ux
description: >-
  Design or improve interfaces with a distinct visual direction, coherent UI
  system, usable interactions, and purposeful motion. Use for new or existing
  web and app interfaces; skip for non-visual code changes.
---

# Clean UI/UX

Create interfaces that feel specific to the product and work well for its users. Make a small number of clear visual and interaction decisions, then carry them through the whole experience.

This skill covers motion in interface interactions and transitions. It does not specialize in standalone motion graphics.

## Workflow

1. **Read the brief and inspect the project.** Identify the audience, user goal, product context, existing brand, framework, component library, and current interaction patterns. Preserve working structure and behavior.
2. **Choose a direction.** Anchor the design in something specific to the product, audience, or content. Set a consistent approach to layout, type, color, spacing, and imagery. Use existing design tokens and libraries when they fit; do not add a competing system or dependency without need.
3. **Build for the actual task.** Keep the interface hierarchy clear and the visual details coherent. Use real content and available assets. Do not add decorative elements or animation without a job to do.
4. **Check usability and motion.** Review responsive layouts, text reflow, contrast, keyboard access, focus, touch targets, loading and error states, and reduced-motion behavior as relevant to the change. Animation should communicate state, guide attention, or add deliberate delight; keep frequent interactions quick and quiet.
5. **Inspect the result.** Use available browser or preview tools when they can reveal layout or interaction problems. Fix the most visible issues before reporting completion. Do not claim checks you did not run.

## Decision rules

- Follow the user's requested style and the product's existing conventions. When they conflict, preserve the user's intent and explain material tradeoffs.
- Prefer a few product-specific details over generic decoration or familiar template patterns.
- Choose components and motion for their context. Avoid universal rules for a single aesthetic, timing, or animation style.
- Treat accessibility and reduced motion as requirements where applicable, not finishing polish.
- For a focused UI bug, make the smallest correction that fixes the observed issue. For a new visual direction, establish shared tokens before styling individual screens.
- Ask only when a missing decision would materially change the design and cannot be inferred from the brief or project.

## Inspiration

This original synthesis was informed by public work from [Taste Skill](https://github.com/Leonxlnx/taste-skill), [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill), and [Design Motion Principles](https://github.com/kylezantos/design-motion-principles). These links are attribution only; this plugin bundles its own workflow and does not load or invoke those skills.
