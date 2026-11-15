---
name: web-ui-director
description: Design, implement, or review web and native UI, including layout, typography, components, responsive behavior, accessibility, and interaction. Use for UI changes, visual reviews, and presentation typography.
---

# Web UI Director

Read applicable project instructions, design references, and existing components before making design decisions. Identify the user's primary action, required content and states, supported screen sizes and input methods, and the actual entry point. Follow explicit design requirements and preserve useful project conventions.

1. **Put the task first.** Learning pages, tools, and workspaces open directly on their content and essential controls. Use a compact title for orientation and place help beside the relevant operation. Remove decorative numbers, oversize covers, slogans, redundant instructions, and decorative illustrations. Use a cover or promotional opening when the brief calls for one.
2. **Organize content on a grid.** Establish the content area, margins, gutters, shared edges, spans, and vertical rhythm before styling components. Let priority determine the layout. Change spans and ordering at narrow widths while preserving reading order, content relationships, and operable controls. See [grid and typography](references/grid-and-typography.md).
3. **Enforce a six-unit type scale.** Every authored UI, web, and presentation font size is a positive multiple of six in the platform's nominal text units. Give each semantic role one font-size token per layout mode. Switch shared tokens in discrete steps and preserve browser zoom and system text enlargement. Include controls, tables, help, captions, and UI charts. Scientific figures follow their own typography rules, including when embedded in a UI or slide. Spacing and line height are independent.
4. **Extend the existing design system.** Reuse components and semantic tokens where they meet the task. Assign colors to roles and verify rendered contrast. Use text, icons, or shape as well as color for important meaning. Respect native platform conventions. Use imagery when it helps the task. Read [visual direction](references/visual-direction.md) when the brief calls for a new palette, materials, or motion.
5. **Make interaction work end to end.** Implement relevant loading, empty, error, success, disabled, hover, focus, and selected states. Provide semantic labels, keyboard access, visible focus, and clear feedback. Keep motion purposeful, interruptible, and compatible with reduced-motion settings.
6. **Verify the delivered entry point.** Run project checks and exercise the interface with the appropriate browser or native tool. Check wide, intermediate, and narrow layouts, both sides of breakpoints, long text, text enlargement, focus, contrast, and relevant states. Fix observed issues and report what was verified. See [implementation and review](references/ui-workflow.md) for the detailed checks.

For review requests, prioritize findings by user impact and cite the affected component and reproducible condition. Apply feedback at the scope the user confirmed. When the project maintains design guidance and the user has authorized updating it, record the decision there with its scope.
