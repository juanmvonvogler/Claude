# flows/

Multi-stage workflows that chain agents and skills together into a repeatable process. Each flow file describes the sequence, the hand-offs, and the exit criteria for each stage.

**What belongs here:** flow definitions — which agents participate, in what order, and how output moves between them (e.g., research → design → build → qa, or the nightly capture-and-summarize pattern that feeds a morning dashboard).

**What does NOT belong here:** the agents or skills themselves (those have their own folders), and any concrete project state. Flows are templates for how work moves, not records of specific work done.
