---
maturity: "OPEN-QUESTION"
claim_type: "EXTERNAL-RESEARCH"
scope: "GENERAL"
version: "6.2"
title: "Academic Lineage"
source_basis:
---
# Academic Lineage

This directory situates **Power Dynamics** and selected kOA mechanisms beside established academic traditions that study the same classes of problems.

> **This is a lineage of problems, concepts, and convergent mechanisms — not a claim of historical influence, endorsement, or proof.**

A cited author may have identified a problem that Power Dynamics also identifies, formalized a mechanism that helps explain a Power Dynamics claim, or supplied a counterexample / impossibility result that a kOA mechanism must survive. None of that means the author endorsed kOA, and none of it validates a particular implementation.

## Why this layer exists

Power Dynamics crosses fields that are usually separated: political theory, organizational sociology, institutional economics, social choice, network science, open-source governance, systems theory, science and technology studies, social epistemology, expertise research, and software architecture.

The purpose of this directory is therefore to make four things explicit for each major connection:

1. **Academic finding or problem** — what the literature actually established or argued.
2. **Power Dynamics correspondence** — which concept, audit surface, or kOA mechanism is structurally related.
3. **Design implication** — what should be tested, measured, separated, or protected.
4. **Limit of correspondence** — what the citation does **not** prove.

## High-level map

| Academic lineage | Problem / insight | Power Dynamics correspondence |
|---|---|---|
| Dahl; Bachrach & Baratz; Lukes | power includes decisions, agenda control, and preference shaping | pre-political chain; discoverability; narrative / classification power |
| Emerson; Cook et al.; Pfeffer & Salancik | power grows from dependency and scarce alternatives | effective possibility; dependency-exit audit; strong capability / weak sovereignty |
| French & Raven; Bourdieu | power has multiple bases and convertible forms | power domains; cross-domain conversion; credibility ≠ authority |
| Pettit | freedom requires protection against arbitrary domination | non-domination terminality; contestation; credible exit |
| Ostrom; Crawford & Ostrom | polycentric governance and institutional rules can be analyzed at multiple levels | federation; subsidiarity; rules-about-rules; constitutional architecture |
| Simon; Baldwin & Clark | complex systems can remain evolvable through modularity and explicit interfaces | capsules; protocolization; branch ecology; local variation + compatibility |
| Farrell & Saloner; Katz & Shapiro; Pierson | compatibility can create lock-in, installed-base power, and path dependence | protocol power; ossification audits; migration paths; version pluralism |
| Hirschman; Nyman & Lindman; O'Mahony & Ferraro; Benkler | exit, voice, forking, peer production, and open governance constrain hierarchy | forkability; branch mobility; founder decentering; capability commons |
| Freeman; Bonacich; Granovetter; Burt; Coleman | network position, brokerage, weak ties, and social capital alter effective capacity | network / affiliation power; mobilization; brokerage and dependency audits |
| Chi; Ericsson & Lehmann; Goldman | expertise is structured, domain-bounded, and difficult for nonexperts to evaluate | SmartVote domain scopes; EkoH context; expertise → advice, not sovereignty |
| Cooke; Budescu & Chen; Mannes et al.; Hong & Page | calibrated weighting can help, but diversity and aggregation rules matter | plural lenses; measured contribution; diverse advisory readings |
| Arrow; Gibbard; Satterthwaite | collective choice mechanisms face structural impossibility and manipulation limits | SmartVote transparency; baseline vs advisory lenses; no universal perfect voting rule |
| Campbell; Merton | metrics and prestige can self-reinforce and be gamed | EkoH / reputation audits; Matthew effects; anti-Goodhart safeguards |
| Winner; Lessig; Bowker & Star; Star & Ruhleder | artifacts, code, classifications, and infrastructure embed governance | power surface; semantic power; interface power; hidden sovereignty |
| Fricker; Goldman; argumentation / belief-revision traditions | epistemic standing, testimony, disagreement, and revision are power-laden | Kristal provenance; competing Kristals; epistemic authority corruption tests |
| Ashby; Beer; Meadows | viable systems require feedback, requisite variety, adaptation, and attention to leverage points | Know → Choose → Act → Remember; local autonomy; feedback; systemic audits |
| Olson; McCarthy & Zald; Granovetter thresholds; Rogers; Centola | collective action requires mobilization, diffusion, threshold crossing, and sometimes social reinforcement | mobilization flow; latent resources; cultural corridors; adoption cascades |
| Sen; Arendt; James C. Scott | real capability, concerted action, and dangers of administrative legibility | effective possibility; generated collective puissance; plural / contestable legibility |

## Reading order

1. [`01-power-dependence-and-domination.md`](01-power-dependence-and-domination.md)
2. [`02-polycentric-governance-and-institutions.md`](02-polycentric-governance-and-institutions.md)
3. [`03-modularity-standards-and-path-dependence.md`](03-modularity-standards-and-path-dependence.md)
4. [`04-open-source-exit-fork-and-peer-production.md`](04-open-source-exit-fork-and-peer-production.md)
5. [`05-network-power-and-social-capital.md`](05-network-power-and-social-capital.md)
6. [`06-expertise-smartvote-and-collective-judgment.md`](06-expertise-smartvote-and-collective-judgment.md)
7. [`07-metrics-reputation-and-gaming.md`](07-metrics-reputation-and-gaming.md)
8. [`08-classification-infrastructure-and-code.md`](08-classification-infrastructure-and-code.md)
9. [`09-epistemic-power-provenance-and-plurality.md`](09-epistemic-power-provenance-and-plurality.md)
10. [`10-systems-cybernetics-and-adaptation.md`](10-systems-cybernetics-and-adaptation.md)
11. [`11-collective-action-mobilization-and-diffusion.md`](11-collective-action-mobilization-and-diffusion.md)
12. [`12-capabilities-concerted-power-and-legibility.md`](12-capabilities-concerted-power-and-legibility.md)
13. [`BIBLIOGRAPHY.md`](BIBLIOGRAPHY.md)

## Core caution

Academic literature can support a **problem diagnosis**, a **mechanism**, an **impossibility constraint**, or a **design principle**. It does not automatically validate:

- a specific SmartVote weighting formula;
- an EkoH scoring implementation;
- the security or decentralization of a current deployment;
- a claim that kOA is optimal;
- a claim that Power Dynamics is derived from these authors;
- or a claim that any cited scholar endorses kOA.

The strongest use of this literature is adversarial: **it gives the framework better names for failure modes and better tests for whether the architecture actually solves them.**
