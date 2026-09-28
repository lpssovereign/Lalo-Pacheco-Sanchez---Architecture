# Public Portfolio Boundary

This repository is an evidence layer, not a source-code mirror of the private production portfolio.

## Public by design

Architecture diagrams, sanitized sequence/data flows, design rationale, authority models, interface screenshots with sensitive information removed, ADR-style decisions, case studies, commodity integration patterns, and selected non-proprietary code may be published when they demonstrate capability without materially enabling reproduction of protected systems.

## Remains private

Production orchestration engines, proprietary ontology and routing logic, reusable workflow libraries, private prompts/instructions where they create implementation leverage, evaluation machinery, production adapters, customer configuration, secrets and credentials, private data, deployment infrastructure, and other implementation assets that materially reduce the cost of reproducing the system remain private.

## Evidence standard

Every public case study should label claims as one of:

- **Implemented** — present in the underlying repository/code.
- **Partially implemented** — meaningful implementation exists but the complete runtime is not yet operational.
- **Specified** — architecture/product contract exists, but implementation is not represented as complete.
- **Exploratory** — research or future direction only.

The purpose is to make technical credibility inspectable without turning roadmap language into false shipping claims.
