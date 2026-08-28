# PAUL vs LSD

**PAUL vs LSD v1.0** is a governed reasoning and execution framework. PAUL supplies the control loop—**Plan → Apply → Qualify → Authority Gate → Unify**—while LSD supplies controlled divergence. The Beckman application layer routes work through **Listen → Search → Decide → Dream**.

It is designed to make reasoning and action legible without turning routine work into a ceremony.

## What problem it solves

A response can be relevant, fluent, emotionally compelling, or well-supported and still lack authority to decide or act. PAUL vs LSD keeps those transitions distinct:

```text
relevance → candidate → qualification → authority
```

Recognition creates an obligation to evaluate; it does not create an obligation to obey. A candidate is not a conclusion. Procedural closure is not epistemic closure.

## When to use it

Use PAUL vs LSD when stakes, ambiguity, novelty, disagreement, irreversibility, or evidence conflict call for a visible decision process. Keep it light for routine, reversible work.

Do not use it to manufacture certainty, substitute process for domain expertise, or turn symbolic material into factual evidence.

## Execution flow

```text
Question
  ↓
PLAN
  ↓
APPLY
  ↓
Candidate(s)
  ↓
QUALIFY
  ↓
AUTHORITY GATE
  ↓
UNIFY
  ↓
Bounded output + decision record + open issues
```

- **Plan** bounds the question, scope, and acceptance criteria.
- **Apply** performs the bounded work; LSD may generate controlled alternatives.
- **Qualify** tests candidates against evidence, assumptions, and falsifiers.
- **Authority Gate** determines what, if anything, may be concluded or authorized.
- **Unify** produces the permitted output, a receipt, and remaining issues.

## Authority

Authority is permission to make or authorize a specified conclusion or action within a stated scope. It is not confidence, fluency, emotional force, symbolic resonance, attention, or repeated agreement.

Authority statuses are:

- Hypothesis
- Working conclusion
- Qualified recommendation
- Authorized decision
- Rejected / quarantined

## Mythic quarantine

Mythic or symbolic material may generate questions, alternatives, assumptions, or falsifiers. It may not independently establish facts, raise empirical confidence, determine responsibility, resolve factual disagreement, or authorize consequential action. Mythic illuminates but does not govern.

## Successful output

A successful run yields a bounded answer or action, a decision record, stated limitations, explicit falsifiers, and open issues where appropriate. Valid final states include `DONE`, `DONE_WITH_CONCERNS`, `NEEDS_CONTEXT`, `BLOCKED`, and `QUARANTINED`.

## Try it

1. Start with [SKILL.md](SKILL.md).
2. Choose a template in [templates/](templates/).
3. Compare protocol densities in [examples/](examples/).
4. Use [tests/framework-invariants.md](tests/framework-invariants.md) to check that an implementation preserves the framework.

## v1.0 status

The canonical v1.0 skill is frozen at [versions/v1.0/SKILL.md](versions/v1.0/SKILL.md). The core loop, Authority Gate, Mythic quarantine, statuses, and invariants are frozen in substance. Future substantive changes belong in a later version and must be documented in [CHANGELOG.md](CHANGELOG.md).

## Repository map

- [Architecture](docs/architecture.md)
- [Execution map](docs/execution-map.md)
- [Authority Gate](docs/authority-gate.md)
- [Decision record](docs/decision-record.md)
- [Examples](examples/README.md)
