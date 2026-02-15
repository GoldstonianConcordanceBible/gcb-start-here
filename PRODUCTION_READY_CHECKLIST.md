# Production Ready Checklist (Tier 1)

This checklist is run against:
- gcb-canon-core
- canonical-index
- (optional) gcb-dao-community-support-token

## A) Docs / Clarity
- [ ] README states purpose + inputs/outputs + quickstart
- [ ] LICENSE present
- [ ] NOTICE present
- [ ] CITATION.cff present
- [ ] CHANGELOG.md present

## B) Versioning / Releases
- [ ] At least one tagged release exists
- [ ] Release notes describe changes
- [ ] Version file present (VERSION or in spec header)

## C) Automation
- [ ] CI enabled and passing
- [ ] Schema validation runs in CI
- [ ] Link checker runs in CI (README + docs)

## D) Data Integrity (canonical-index)
- [ ] Schemas exist and match exports
- [ ] Exports are reproducible via scripts/
- [ ] SHA256SUMS.txt published with releases

## E) Governance Safety (token repo, if used)
- [ ] DAO_CHARTER.md contribution-only
- [ ] PROPOSAL_TEMPLATE.md exists
- [ ] ATTESTATION_LOG.md exists
- [ ] MARKETING_COMPLIANCE.md exists
- [ ] CI flags “investment/ROI” language

## Final Gate
- [ ] All Tier 1 repos green CI + release tags + checklist complete

If all boxes are checked: **ALL IS PRODUCTION READY**