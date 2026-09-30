# Legal Technology Positioning

## Target lane

I am positioning for **legal technology, legal AI, AI enablement, legal operations technology, solutions architecture, implementation, and applied AI roles** where the work is to translate ambiguous professional workflows into governed, production-oriented systems.

I am **not** presenting myself as an attorney. My value is in systems design, workflow decomposition, provenance, orchestration, implementation, and human-in-the-loop governance.

## Why this fits my architecture work

The current legal-tech market is increasingly asking for people who can:

- translate legal/business workflows into AI-enabled systems;
- design repeatable, auditable AI workflows;
- connect LLMs to enterprise data, APIs, and systems of record;
- preserve permissions, provenance, and review boundaries;
- create synthetic or controlled test data;
- build proof-of-concept workflows and implementation playbooks;
- work across legal, operations, IT, security, product, and business stakeholders;
- move from experimentation to measurable adoption.

My public portfolio demonstrates those same patterns through PhiNeX, SOPHIA, Vizion, Kairos, and Marathon.

## Legal-tech capability map

| Market need | Portfolio evidence |
|---|---|
| AI-enabled legal workflows | PhiNeX evidence-to-resolution architecture |
| Human review and approval | SOPHIA authority model + PhiNeX approval gates |
| Matter-state persistence | PhiNeX case graph + structured decision objects |
| Source-grounded analysis | provenance, evidence links, authority status, freshness |
| Legal operations automation | procedure routing, deadlines, obligations, handoffs |
| Intake / issue triage | consumer-protection front door + structured matter creation |
| Workflow orchestration | bounded agents, state transitions, approval gates |
| Auditability | append-only receipts and execution verification |
| Privacy / data boundaries | private tenants, purpose-separated stores, de-identification |
| AI governance | authority, jurisdiction, revocation, escalation, receipts |
| Implementation architecture | APIs, FastAPI services, SQLite/Postgres patterns, event/state models |
| Adoption / operational UX | role-aware workbenches, principal briefs, next-action views |

## Flagship legal-tech case: PhiNeX

PhiNeX is a governed **consumer-protection and adversarial-resolution architecture**.

The core design problem is not simply legal drafting. It is preserving a reliable state of a matter across the full lifecycle:

```text
problem signal
-> evidence
-> assertions / facts / contradictions
-> claims / defenses / obligations
-> adversarial testing
-> remedy / procedure routing
-> professional review
-> principal decision
-> scoped authorization
-> execution receipt
-> resulting obligations
-> verified resolution
```

The private implementation and current development branches include or specify:

- purpose-separated evidence, case, legal-intelligence, counsel, corpus, and audit stores;
- typed assertions and source provenance;
- legal-source status and freshness;
- case, pattern, and program tenants;
- contradiction and adverse-fact handling;
- commitments, obligations, procedures, and deadlines;
- counsel handoff boundaries;
- de-identification and corpus admission controls;
- explicit approval gates for consequential actions;
- append-only audit receipts;
- Principal Decision Readiness objects;
- current product work on consumer-protection intake, adversarial matter state, strongest-case / strongest-countercase testing, counsel continuity, and verified resolution.

This is intentionally not positioned as autonomous legal representation.

## Recruiter-facing role fit

The strongest current fit is not "software engineer who happens to like law."

It is a hybrid lane:

### Legal Technology Solutions Architect
Translate attorney, legal-ops, compliance, and business workflows into reliable AI-enabled systems.

### Applied AI / Implementation Architect — Legal
Own discovery, technical scoping, workflow design, integrations, proof-of-concept builds, governance, and rollout.

### Legal AI Enablement / Innovation
Help legal teams adopt LLMs, agents, knowledge systems, and workflow automation safely and measurably.

### Legal Operations Technology
Connect matter workflows, approvals, documents, obligations, analytics, and AI-assisted work.

### AI Governance for Legal / Compliance
Design authority, review, auditability, and action controls around AI-assisted professional work.

## What differentiates my profile

I approach legal AI as an **operating-system problem**, not only a prompt problem.

The recurring architecture questions are:

1. What is the authoritative state of the matter?
2. Which assertions are supported, disputed, inferred, or unresolved?
3. Who is authorized to decide or act?
4. Which action requires professional or human review?
5. What source or evidence supports the output?
6. What changes when an action executes?
7. Can the system prove what was authorized and what actually happened?
8. Does resolution create new obligations that must be monitored?
9. Can useful pattern intelligence be derived without exposing private matters?

That framing transfers directly to legal AI, legal operations, compliance systems, enterprise AI implementation, and regulated workflow automation.

## Current stack represented across the portfolio

- Python
- FastAPI
- REST APIs and integrations
- SQLite with migration path to Postgres
- React / Vite
- OAuth / delegated authorization
- event-driven orchestration
- structured JSON object contracts
- retrieval / provenance patterns
- LLM-assisted workflows
- local and cloud model orchestration
- governance gates
- audit/event receipts
- human-in-the-loop execution
- Linux / systemd service operation

## Portfolio navigation

- [PhiNeX — Governed Evidence-to-Resolution Infrastructure](../case-studies/phinex.md)
- [SOPHIA — Governance & Constitutional Authority for Agentic Systems](../case-studies/sophia.md)
- [Vizion — Governed How-To Runtime](../case-studies/vizion.md)
- [Marathon — Work Reconciliation](../case-studies/marathon.md)
- [Kairos — Relationship and Communication Intelligence](../case-studies/kairos.md)

## Public / private boundary

This dossier shows architecture, system behavior, and sanitized patterns. It does not expose private case evidence, proprietary prompts, production secrets, protected implementation details, or confidential records.
