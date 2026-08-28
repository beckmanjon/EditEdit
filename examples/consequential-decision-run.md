# Consequential decision run

> Synthetic scenario

## Question

May a team suspend a customer-facing workflow after detecting a plausible but unverified error pattern?

## Plan

- **Scope:** Recommend an immediate response; do not determine fault.
- **Complexity budget:** High because the action is consequential and potentially irreversible.
- **Acceptance criterion:** Protect against harm without claiming facts beyond the evidence.

## Apply and Qualify

The team has several reports suggesting a pattern, but the evidence has not yet established cause, frequency, or affected scope. A candidate to suspend the workflow is coherent as a precaution. It remains a candidate because evidence and decision authority are incomplete.

## KDP / final decision gate

- **Qualification:** The precaution is coherent but does not establish cause.
- **KDP authority available:** The team may prepare evidence and notify the designated incident owner.
- **Authority missing:** Authorization to suspend the customer-facing workflow.
- **Correct action:** Escalate with the bounded recommendation and evidence receipt.

## Unify

Prepare a concise incident packet and request the designated owner’s decision on suspension.

- **Falsifier:** Verified reports showing the pattern is unrelated or outside the workflow.
- **Consequence-review point:** Reassess immediately after the owner’s decision or new evidence.
- **Final status:** `BLOCKED`

A coherent candidate did not become an action merely because it sounded prudent.