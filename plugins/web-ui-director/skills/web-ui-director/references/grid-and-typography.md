# Grid and typography

## Compose with a grid

- Define the usable content area after accounting for navigation. Establish the main reading edge, maximum width, margins, gutters, and recurring anchors.
- Use a single text block for sustained reading, columns for primary and supporting material, modules for comparable entries, and a hierarchical grid for unequal priorities. Add a baseline guide where text across columns needs to line up.
- Align media and captions to the same span. Connect nested layouts to the parent grid or give them a deliberate inset. Use span, placement, contrast, and whitespace to create emphasis.
- Choose body leading before setting vertical rhythm. Check rendered baselines for mixed scripts and fonts. Allow text to wrap and let sections grow with their content.

## Apply the six-unit scale

Choose from 12, 18, 24, 30, 36, 42, and higher multiples of six as needed for legibility. Map nominal values to CSS pixels on the web, points in presentations, and logical text units in native UI. For example, 1.125rem represents 18 CSS px at a 16px default root. Keep user-controlled scaling.

Define a shared font-size token for each semantic role. Map library defaults, inline controls, chart legends and axes, SVG and canvas text, and generated labels to those roles. Change the token once per role at a breakpoint. Resolve tight layouts through reflow, wrapping, or wider spans. Check resolved sizes after fonts load, including across component states and around each breakpoint.
