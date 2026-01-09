# Code Release Plan

Remapped Protocol (RMP) publishes code incrementally to reduce attack surface
and prevent surprise behavior changes.

Documentation and specifications are published before executable code.

---

## Phase 0 — Documentation & Specifications (current)
Public:
- Website documentation
- Whitepaper (PDF + Markdown)
- Design specifications (`rmp-specs`)
- Security disclosure policy

Private:
- Chain runtime
- Pallet implementations
- Deployment and infrastructure tooling

---

## Phase 1 — Design Interfaces
Public:
- Architecture descriptions
- Runtime interface specifications
- Threat model

No executable code is published during this phase.

---

## Phase 2 — Skeleton Runtime
Public:
- Runtime structure
- Pallet boundaries
- Types and interfaces
- Non-production wiring

Excluded:
- Genesis configuration
- Production parameters
- Deployment scripts
- Keys or secrets

Repositories in this phase are explicitly non-production.

---

## Phase 3 — Full Runtime & Testnet
Public:
- Complete runtime and pallets
- Testnet configuration
- Developer documentation

Conditions for entering Phase 3 include:
- Multisig custody readiness
- External review or audit intent
- Defined operational processes

---

## Security Considerations
At no stage will the project publish:
- Private keys or secrets
- Infrastructure topology
- Monitoring or emergency tooling
- Undocumented privileged mechanisms

---

## Philosophy
This staged approach prioritizes:
- Predictability
- Auditability
- Operational safety

Transparency is achieved through clarity, not haste.
