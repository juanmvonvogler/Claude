# Capability Framework

The pure capability layer of a Claude-based agent system. This repo defines **how** agents think, communicate, and execute workflows — not **what** they are working on.

## The capability/context split

This framework is deliberately stripped of personal context. It contains zero names, projects, clients, or private data. Personal context lives in a separate private system and is injected at runtime by an **orchestrator agent** that acts as the broker between the two layers.

- **This repo** — reusable capabilities: principles, agents, skills, pipelines, protocols
- **Private context system** — personal knowledge, project state, client information
- **Orchestrator** — bridges the two at session start, never the other way around

The separation is intentional. It lets capabilities be versioned, shared, forked, or published without leaking anything private, and lets personal context evolve without invalidating the framework.

## Layout

- `foundation/` — thin universal layer inherited by every agent
- `agents/` — conversational capability agents, each with its own `soul/` for identity
- `skills/` — reusable capability modules called by agents
- `flows/` — multi-stage workflows chaining agents and skills
- `protocols/` — contracts and interfaces between agents
- `templates/` — starting points for creating new agents and skills
- `docs/` — documentation about the framework itself
