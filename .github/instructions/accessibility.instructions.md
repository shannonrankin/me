---
description: Accessibility rules for website content and styles
applyTo: "**/*.qmd,**/*.md,**/*.css,**/*.yml,**/*.yaml"
---

# Accessibility

- Target WCAG 2.2 AA.
- Use one page title and sequential heading levels. Do not use bold text as a
  substitute for a heading.
- Give informative images concise, contextual alternative text. Use empty alt
  text only for decorative images, and provide a nearby text description for
  complex charts or diagrams.
- Use descriptive link text that makes sense out of context; avoid bare URLs and
  phrases such as "click here."
- Use semantic elements and proper list and data-table markup. Give data tables
  clear headers and captions; never use tables only for layout.
- Do not convey meaning through color, position, shape, or emphasis alone. Keep
  text contrast at least 4.5:1, non-text and large-text contrast at least 3:1,
  and visible keyboard focus indicators.
- Ensure controls are keyboard accessible, layouts work when zoomed, and motion
  respects `prefers-reduced-motion`.
- Provide captions for video and transcripts for audio.
