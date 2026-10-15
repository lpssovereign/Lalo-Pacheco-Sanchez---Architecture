# Tesseract State Intelligence

## Problem
AI systems often compress changing, contradictory, source-dependent reality into a single summary or status. That is convenient, but it can destroy information needed for judgment.

## Architecture pattern
A recurring LPS pattern keeps several layers distinct:

```text
source / observation
-> claim
-> current state + context
-> discrepancy / uncertainty
-> bounded hypothesis
-> governed action
-> verification
-> outcome
-> revision
```

The implementation goal is not "AI that always knows." It is a system that can preserve what is known, what is asserted, what is inferred, what remains unknown, who has authority, what changed, and what evidence caused the change.

## Cross-domain use
The pattern appears in:
- legal/evidence reconstruction;
- learner/capability modeling;
- work reconciliation;
- relationship/timing intelligence;
- governed procedural execution.

## Boundary
This public case study describes architecture and design rationale, not the private schemas, corpora, prompts, or orchestration machinery used by LPS Tesseract.
