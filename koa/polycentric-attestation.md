---
maturity: "DESIGN-DIRECTION"
claim_type: "USER-CONFIRMED-DESIGN"
scope: "kOA"
version: "6.5"
title: "Polycentric Attestation and Recognition Policies"
source_basis:
  - S16
  - S25
  - S31
---
# Polycentric attestation and recognition policies

**Design intent, not deployed protocol documentation.** Institutions may issue attestations and each independent kOA instance may accept them through its own explicit, inspectable, revocable recognition policies. No universal issuer registry or mandatory central authority is required.

## Objects and relations

- **Issuer:** a person or organization making a bounded assertion (qualification, product documentation, experimental result, local permit, professional record, etc.).
- **Attestation:** signed or otherwise independently authenticated statement with subject, claim, scope, provenance, dates, status and possible supporting evidence.
- **Reader / verifier:** person, institution, or instance evaluating an attestation under its own policy.
- **Recognition edge:** directional decision of a reader to accept some classes of attestations from an issuer.
- **Delegation edge:** a *separate*, explicit rule allowing another party to choose qualified issuers under limited conditions; not automatically implied by recognition.
- **Policy:** versioned conditions specifying accepted issuers, domains, claim types, constraints, validity, delegation depth and exclusions.
- **Evidence graph:** provenance and causal dependence of supporting sources, separate from the social graph of endorsements.

## Reciprocal and partial recognition

Examples below are hypothetical:

| Reader | Issuer | Potentially accepted | Not automatically accepted |
|---|---|---|---|
| A UNESCO-like body | Harvard | explicitly named qualifications | every statement by every Harvard employee |
| A university | a UNESCO-like body | selected educational reference attestations | an unrelated political recommendation |
| A developer group | Microsoft | origin/authenticity of Microsoft product docs | the assertion that Microsoft products are objectively best |
| A public-health institute | a qualified lab | methods and results within scope | unreviewed broad political claims |
| A city | sports federation | competency attestations for a local program | statutory licensing powers |

Acceptance may be exact, partial, conditional, time-limited, or denied. Likewise, Harvard or Microsoft may accept all of one issuer's *declared attestation categories* or exclude some, but an unrestricted trust-all setting should display its high-risk implications.

## Evaluation pipeline

```text
Receive credential
  -> authenticate issuer + integrity
  -> check claim type, subject, issuance and expiration
  -> load local reader policy + its version
  -> check explicit issuer/domain/scope match
  -> inspect overrides, exclusions and valid revocations
  -> follow delegation only if explicitly allowed and bounded
  -> inspect evidence quality / independent source lineage
  -> produce qualified reader-specific result + rationale
  -> permit appeal, annotation, comparison or alternative policy
```

An authenticated issuer is not a proof of factual accuracy. A recognized medical researcher does not automatically certify a particular medical claim; independent validation rules remain essential. Even a widely recognized institution may be wrong.

## Defensive properties

1. **No silent transitivity:** trust in B cannot silently turn every institution endorsed by B into an issuer accepted by A.
2. **Domain, purpose, and claim-type boundaries:** evidence attestation, competence certification, factual assertion, editorial position, endorsement, and statutory authorization are different objects.
3. **No global truth/reputation score:** trust is local and contextual, with legible provenance and counterevidence.
4. **Revocation with history:** new acceptance decisions must respect revocations; archival records still preserve what was accepted and why at the time.
5. **Anti-Sybil checks:** many organizations with common control, citations, personnel or origin cannot be counted as many independent proofs.
6. **No dependence on proprietary services:** independent implementations can verify signatures, read policies, migrate evidence and exchange with compatible peers.
7. **Forkable institutions, not inherited mandates:** cloning software or an openly licensed corpus conveys neither another entity's name nor its legal competencies.
8. **Local sovereignty plus interoperability:** common data/exchange formats; divergent governance and acceptance policies.

## Implementation questions

Identity/key lifecycle and recovery; canonical serialization and signature suites; offline verification; cross-instance conflict handling; portable contact/social graphs; license compliance; privacy and right of appeal; path explanation; multi-hop delegated recognition; reciprocal policy change notifications; emergency exclusion vs due process; semantic versioning; governance of shared standards.

A minimal **illustrative**, non-normative policy structure is provided at [`../schemas/recognition-policy.schema.yaml`](../schemas/recognition-policy.schema.yaml) and [`../examples/recognition-policy.example.yaml`](../examples/recognition-policy.example.yaml). It is *not* a production kOA interchange protocol.
