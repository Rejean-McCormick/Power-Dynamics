---
maturity: "EXPERIMENTAL"
claim_type: "ANALYTICAL-RECONSTRUCTION"
scope: "GENERAL"
version: "6.5"
title: "Contested Media Claim: Source Plurality Without Truth by Vote"
source_basis:
  - S31
---
# Contested media claim: source plurality without truth by vote

**Fictional case.** The example is not a statement about any contemporary politician, publisher, institution, or actual economic policy.

## The same true dataset, two incompatible headlines

A public employment dataset reports **100,000 hires** and **60,000 separations** over a stated period in a stated jurisdiction.

- Outlet A: “The policy created 100,000 jobs.” Cites gross hires.
- Outlet B: “The policy created only 40,000 net jobs.” Subtracts separations.
- Statistical source: supports gross entries, exits, and net change. It does *not* by itself identify what portion was caused by the policy.

The numerical disagreement can be explained through measurement choice, while both headlines may overclaim **causation**. A policy-focused causal inference requires an appropriate comparison or model beyond raw counts.

## Proposed claim graph

```text
primary employment dataset
  ├── gross hires = 100,000 ------- Outlet A selected number
  ├── separations = 60,000 -------- omitted or contextualized
  └── net change = 40,000 --------- Outlet B selected number

separate causal claim: "policy caused all net change"
  └── NOT ESTABLISHED by these counts alone
```

A third outlet repeating A does not automatically supply independent confirmation. A source may be trustworthy about a numerical dataset and unreliable on its causal interpretation.

## Reader policies

Reader X may accept the statistical authority's dataset and both articles as authenticated publications but mark one or both causal claims **unsupported**. Reader Y may exclude Outlet A for editorial reasons without changing the validity of the primary data. Reader Z may accept A's number and still flag its framing as potentially misleading.

A good viewer makes those distinctions visible. It should not announce “Outlet B wins 2–1” or identify the most endorsed interpretation as true.

## Audit questions

1. Can readers trace both outlets to the same originating evidence?
2. Are gross flow, net stock, causal inference, and value judgment presented separately?
3. Are the period, population, uncertainty and omissions visible?
4. Can readers compare multiple policies *without* conflating a policy score with empirical truth?
5. Can critical updates change the interpretation without rewriting past attestations?
6. Can forked instances exchange claim IDs, evidence provenance and counterevidence?
7. Does the system resist astroturfing through a thousand copycat validators?

**Failure condition:** The system declares disinformation solely because two channels disagree or because one has fewer endorsers. An actionable diagnosis requires articulated, checkable evidence of material falsity or misleading presentation; intentional disinformation additionally requires evidence of intent.
