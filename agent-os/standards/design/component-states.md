# Component States

Every interactive component defines these states before handoff:

| State | Required | Token pattern |
|-------|----------|---------------|
| Default | Always | Base tokens |
| Hover | Always | `-hover` |
| Focus | Always | `shadow.focus-ring` |
| Active | Always | `-active` |
| Disabled | Always | `opacity: 0.5`, no pointer events |
| Loading | If async | Spinner + `aria-busy` |
| Error | If input | `border.error` + message |
| Selected | If selectable | `interactive.selected-bg` |

- Show feedback within 100ms of a click (state change or loader)
- Motion: 100–300ms, never over 500ms; respect `prefers-reduced-motion`
- Full specs: `components/*.md`
