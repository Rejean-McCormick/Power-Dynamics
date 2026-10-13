---
maturity: "DESIGN-DIRECTION"
claim_type: "ANALYTICAL-RECONSTRUCTION"
scope: "GENERAL"
version: "6.5"
title: "Polycentric Trust and Narrative-Power Audit"
source_basis:
  - S31
---
# Polycentric trust and narrative-power audit

For each test record: actor, issuer, reader, claim, scope, trust policy version, evidence lineage, decision, reason, challenge route, and independent reproduction result. Mark all untested items **UNKNOWN**, never **PASS**.

| Dimension | Adversarial test | Failure signal |
|---|---|---|
| Directionality | A recognizes B; B rejects A | forced reciprocity |
| Partial acceptance | accept some issuer claim types only | issuer-wide blanket acceptance |
| Non-transitivity | A recognizes B, B recognizes C, A has not delegated to C | C silently accepted |
| Bounded delegation | withdraw a delegated issuer domain | existing downstream privileges stay unlimited |
| History / revocation | revoke issuer, then inspect prior published decision | silent history erasure or continued unqualified acceptance |
| Authenticity vs truth | issuer accurately signs an empirically false claim | signed claim called true |
| Base rates | show ten true extreme-success stories vs population distribution | exceptional possibility presented as prevalence |
| Independence | 100 syndicated articles derive from one report | 100 independent sources counted |
| Causal ambiguity | accurate dataset with misleading policy-causation headline | unearned causal validation |
| Fork / founder capture | founder disables service or changes policy | independent instances cannot continue |
| Institutional substitution | alternative group deploys, migrates and seeks recognition | original owner's permission required |
| Open Good | remove proprietary identity/hosting services | federation stops functioning |
| Standards governance | original maintainer rejects compatible community implementation | arbitrary network exclusion |
| Legal boundary | clone technical infrastructure of public authority | clone falsely implies same legal mandate |
| Sybil / collusion | mutually approving synthetic institutions | circular prestige counted as independent evidence |

## Suggested pilot measures

- independent installations that survive loss of founding service;
- successful bilateral exchange between differing recognition policies;
- correct detection of out-of-scope and revoked attestations;
- provenance independence ratio (unique causal origins / visible citations);
- ability to explain rejection and contest it;
- user ability to distinguish **issuer authenticity**, **claim support**, **policy acceptance** and **legal authorization**;
- cost and completeness of data/contact/policy migration.

Do not compress these into a global truth score or rank of institutional virtue. Publish the conditions, error rates, missing data and what remains unverified.
