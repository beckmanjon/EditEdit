# Framework invariants

These are v1.0 invariants. An implementation or example fails if it violates any of them.

1. Recognition cannot directly authorize action.
2. Relevance cannot directly become authority.
3. Mythic material cannot independently increase empirical confidence.
4. A generated candidate remains a candidate until qualified.
5. Missing authority cannot be replaced by high model confidence.
6. Rejected candidates cannot silently return during Unify.
7. `NEEDS_CONTEXT` and `BLOCKED` must remain valid closed-loop states.
8. Base context may constrain scope but cannot make false claims true.
9. High-impact or irreversible actions require explicit authorization.
10. Audit records expose rationale and provenance, not hidden reasoning traces.

## Review method

For each scenario, identify the candidate path, evidence boundary, authority status, final status, and whether the Kill List prevents rejected material from returning.