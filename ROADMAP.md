# GCB Roadmap

## Phase 0 — Front Door (Now)
- gcb-start-here repo created
- org pins updated to highlight Tier 1 repos

## Phase 1 — Canon Spec v0.1 (gcb-canon-core)
Deliverable: a minimal, stable spec that agents can depend on.
- GCB-SPEC.md
- DOCTRINE.md
- INTERPRETIVE_RULES.md
- GLOSSARY.md
- SCHEMAS/ (doctrine, claim, citation, prompt, proposal)
- CI validates schemas + required files
- Tag: v0.1.0

## Phase 2 — Canonical Index as Data Product (canonical-index)
Deliverable: validated datasets + reproducible exports.
- scripts/validate.py
- scripts/build_exports.py
- CI runs validate/build/link checks
- Release artifacts include exports + SHA256SUMS.txt
- Tag: v1.0.0 (or vYYYY.MM.DD)

## Phase 3 — Governance Stack (optional public-facing)
Deliverable: contribution-only governance, no investment framing.
- DAO_CHARTER.md
- PROPOSAL_TEMPLATE.md
- ATTESTATION_LOG.md
- CI keyword guardrails for marketing language
- Tag: v1.0.0

## “ALL IS PRODUCTION READY” Gate
All Tier 1 repos pass PRODUCTION_READY_CHECKLIST.md with green CI + releases.