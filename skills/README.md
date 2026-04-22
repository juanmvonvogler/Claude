# skills/

Reusable capability modules — called **by** agents, not used standalone. Each skill is self-contained, focused on a single capability, and invokable by any agent that needs it.

**What belongs here:** generic capabilities with clear inputs and outputs — writing style rules, design system helpers, QA checklists, and similar building blocks.

**What does NOT belong here:** anything agent-specific (those live under `agents/<name>/`), and anything carrying personal voice, project specifics, or private data. Skills should be generic enough to reuse across users and contexts.
