# agents/

Conversational capability agents — entities you interact with directly in a session. Each subdirectory is one agent with a `SKILL.md` entry point and an optional `scripts/` folder for helpers.

**What belongs here:** agents defined by their role and working style (e.g., coding partner, researcher, orchestrator). Each one should be a pure capability — its behavior is defined without reference to any specific project or user.

**What does NOT belong here:** personal context, project state, or private data. Agents receive that at runtime from the orchestrator via a context brief (see `protocols/context-brief-schema.md`).
