# Design Tokens

Never hardcode color, size, spacing, radius, or shadow values. Reference a token.

| Tier | Use in | Example |
|------|--------|---------|
| Primitive | Never directly | `blue.600` |
| Semantic | Designs, general styling | `action.primary` |
| Component | Component code | `component.button.primary-bg-hover` |

- Naming: `{category}.{property}.{variant}-{state}`
- Format: DTCG (`$type` / `$value`)
- Dark mode swaps semantic tokens only; primitives never change
- Spacing is a multiple of 4px; prefer semantic aliases (`card.padding`, `stack.lg`)
- Source files: `tokens/*.json`
