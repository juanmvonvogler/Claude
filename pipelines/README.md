# pipelines/

Multi-stage workflows that chain agents and skills together into a repeatable process. Each pipeline file describes the sequence, the hand-offs, and the exit criteria for each stage.

**What belongs here:** workflow definitions — which agents participate, in what order, and how output flows between them (e.g., research → design → build → qa).

**What does NOT belong here:** the agents or skills themselves (those have their own folders), and any concrete project state. Pipelines are templates for how work moves, not records of specific work done.
