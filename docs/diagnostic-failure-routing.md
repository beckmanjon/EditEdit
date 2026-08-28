# Diagnostic failure routing

When a run fails to meet acceptance criteria or encounters a material defect, classify the root cause before patching:

- **Intent issue** — the requested or locked question is wrong, incomplete, or mis-specified.
- **Spec issue** — the acceptance criteria, scope, or constraints are insufficient or contradictory.
- **Evidence gap** — necessary information is missing, conflicting, or outside the evidence boundary.
- **Structural blocker** — an external dependency, authority, capability, or condition prevents progress.

Route the result to a bounded repair, re-lock, escalation, `NEEDS_CONTEXT`, or `BLOCKED`. Do not paper over a routing failure with a confident conclusion.