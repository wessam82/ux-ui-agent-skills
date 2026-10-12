# Agent OS

Project memory for the Agent OS skills in `.claude/skills/agent-os-*`.

| Folder | What lives here | Written by |
|--------|-----------------|------------|
| `standards/` | Short, agent-readable rules, plus `index.yml` for matching | `/agent-os-discover-standards`, `/agent-os-index-standards` |
| `product/` | `mission.md`, `roadmap.md`, `tech-stack.md` | `/agent-os-plan-product` |
| `specs/` | One dated folder per shaped feature | `/agent-os-shape-spec` |

## Typical flow

1. `/agent-os-plan-product` — define mission, roadmap, tech stack
2. `/agent-os-discover-standards` — capture your team's conventions
3. Enter plan mode, then `/agent-os-shape-spec` — shape the feature
4. `/agent-os-inject-standards` — load the right rules before building

The seeded standards summarize this repo's `CLAUDE.md`. Edit them, then run `/agent-os-index-standards`.

Source: [Agent OS v3](https://github.com/buildermethods/agent-os) by Brian Casel @ Builder Methods, MIT license (see `LICENSE` in this folder).
