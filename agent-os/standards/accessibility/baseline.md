# Accessibility Baseline

WCAG 2.2 AA is the minimum. Every component passes these before it ships:

- Keyboard: Tab reaches it, Enter/Space activates it
- Focus ring visible at 3:1 contrast and not hidden by sticky headers (2.4.11)
- Contrast: 4.5:1 for text, 3:1 for UI parts and large text
- Target size: 24×24px minimum, 44×44px for primary actions (2.5.8)
- Never use color as the only signal; pair with icon or text
- Screen reader announces name, role, and state
- Auth: no puzzles or memory tests; allow password managers (3.3.8)
- References: `accessibility/wcag-checklist.md`, `accessibility/aria-patterns.md`
