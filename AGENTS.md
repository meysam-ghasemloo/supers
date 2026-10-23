# Frontend Design & UI/UX Guidelines

For all frontend development, UI components, styling, and design tasks in this project, always adhere to the following rules:

## 1. Visual Direction & Anti-Slop (Taste Skill)
- **Avoid AI Clichés**: Never rely on generic AI-generated aesthetics (e.g., overused purple/cyan gradients, identical 3-column feature cards, meaningless glow effects, or decorative empty containers).
- **Art Direction**: Choose distinct, intentional typography pairings, brand-aligned color palettes, and structured layouts based on the subject matter rather than generic defaults.
- Leverage the principles and guidance provided in `.agents/skills/design-taste-frontend/`.

## 2. Engineering & Usability Standards (UI-UX Pro Max)
- **Design Systems & Consistency**: Use semantic color tokens, consistent spacing scales (4px/8px grid), and accessible typography scales.
- **Accessibility (WCAG AA)**:
  - Ensure text contrast is at least 4.5:1.
  - Touch/click targets must be at least 44×44px.
  - Never use icon-only buttons without accessible labels (`aria-label`).
  - Keep keyboard focus rings clearly visible.
- **Responsive & Mobile-First**: Build fluid layouts that adapt seamlessly across mobile, tablet, and desktop without horizontal scroll.
- Leverage the guidelines, UX rules, and component architectures in `.agents/skills/ui-ux-pro-max/`.
