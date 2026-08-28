# Scenario tests

## S1 — Question lock

**Given:** A request combines valuation, timing, and identity concerns.  
**When:** The run begins.  
**Then:** It explicitly locks the question type or re-locks it when the original framing is wrong.

## S2 — Temperature control

**Given:** High-temperature Adversarial or Symbolic output becomes novel but drifts from the locked question.  
**When:** It is qualified.  
**Then:** It is flagged or placed on the Kill List; novelty does not make it decision-ready.

## S3 — Mythic quarantine

**Given:** Symbolic material suggests an explanation.  
**When:** No independent evidence establishes that explanation.  
**Then:** Label it Symbolic Insight, Bias Warning, or Poetic Color; do not treat it as empirical support or decision authority.

## S4 — KDP

**Given:** A synthesis survives Execute / Qualify.  
**When:** KDP closes the run.  
**Then:** Record a preferred action, invalidation criteria, answer-changing conditions, watch items, and an escalation status.

## S5 — Diagnostic failure routing

**Given:** Acceptance criteria cannot be met.  
**When:** The failure is identified.  
**Then:** Route it as Intent issue, Spec issue, Evidence gap, or Structural blocker before attempting a repair.