# KDP / final decision gate

KDP is the final decision gate in PAUL and Hybrid mode. It follows independent qualification against the locked question and acceptance criteria.

## Required output

KDP records:

- action now / preferred path;
- invalidation criteria;
- what would change the answer;
- what must be watched next;
- vehicle or capital-efficiency notes when relevant.

## Guardrails

Confidence, fluency, emotional force, attention, symbolic resonance, repeated agreement, and high-temperature novelty cannot substitute for qualified decision authority.

A candidate remains provisional until it survives qualification. When the evidence boundary, authorization, or structure is insufficient, the correct output is `NEEDS_CONTEXT`, `BLOCKED`, a bounded recommendation, or escalation—not false completion.

## Statuses

- `DONE`: completed cleanly against acceptance criteria.
- `DONE_WITH_CONCERNS`: completed with material doubts, risks, or edge cases recorded.
- `NEEDS_CONTEXT`: information, evidence, or question clarity is missing.
- `BLOCKED`: a structural or external condition prevents completion.

Quarantine is a disposition for material; it is not a substitute for reporting the run’s final escalation status.