---
maturity: "CURRENT-CORE"
claim_type: "ANALYTICAL-RECONSTRUCTION"
scope: "GENERAL"
version: "4.0"
title: "Power Dynamics"
source_basis:
  - S01
  - S02
  - S10
  - S13
  - S15
  - S16
  - S18
  - S21
  - S22
  - S25
  - S26
---
# Power Dynamics

**A systems theory of effective possibility, puissance, and relational power.**

Power Dynamics studies the full lifecycle through which resources become usable capabilities, capabilities become effective **puissance**, puissance enters **power relations**, and the effects of those relations return to the system as new resources, dependencies, institutions, alternatives, memories, and possibilities.

The repository reconciles two complementary levels of analysis:

1. a **strict ontology** that prevents category errors;
2. a **dynamic theory** that follows how capacity and power form, move, combine, convert, accumulate, concentrate, contest, diversify, and decay.

The core ontology is:

> **Resources / Assets → Potential → Capacity → Puissance → Power Relations → Effects → Returns**

The core dynamic loop is:

> **Stock → Potential → Capacity → Puissance → Mobilization → Relation / Effect → Return → New Stock**

Neither model replaces the other. The ontology answers **what kind of thing is this?** The dynamics answer **what is happening to it?** A third layer identifies **where** the process occurs: economic, epistemic, technical, political, reputational, semantic, infrastructural, narrative, administrative, mnemonic, cognitive, or other domains.

## Start here

1. [`GLOSSARY.md`](GLOSSARY.md) — canonical terminology.
2. [`framework/01-core-ontology.md`](framework/01-core-ontology.md) — resource, potential, capacity, puissance, power, effect, return.
3. [`framework/03-three-axis-model.md`](framework/03-three-axis-model.md) — ontology × dynamics × domains.
4. [`dynamics/README.md`](dynamics/) — how capability and power change over time.
5. [`PRINCIPLES.md`](PRINCIPLES.md) — constitutional constraints.
6. [`koa/README.md`](koa/) — kOA as the primary systems case.
7. [`assessment/analysis-method.md`](assessment/analysis-method.md) — how to audit a real system.

## Why the distinction matters

Money is not automatically power. A reputation is not automatically authority. A codebase is not automatically control. A large unpublished corpus is not stored power. These are resources or reservoirs. They create potential; potential can become capacity; capacity can become effectively mobilizable puissance. **Power appears relationally** when that puissance changes another actor's effective possibilities through access, allocation, ranking, recognition, authorization, enforcement, dependence, coordination, definition, or other mechanisms.

At the same time, Power Dynamics is deliberately broader than a theory of domination. It studies:

- **power to** as puissance d'agir;
- **power with** as collective and associative puissance;
- **power through** as infrastructure-mediated puissance;
- **power over** as asymmetric relational power;
- positive and generative capability;
- cross-domain conversion and concentration;
- returns, reinvestment, and compounding;
- counterpower, exit, substitution, forkability, and branch mobility;
- plurality, complementarity, and evolutionary governance.

## Three-axis analytical model

Every serious analysis should locate a phenomenon on three axes.

### Axis A — Ontological state

`Resource → Potential → Capacity → Puissance → Power Relation → Effect → Return`

### Axis B — Dynamic process

`Formation → Mobilization → Composition → Conversion → Return → Reinvestment → Compounding → Concentration / Capture → Contestation → Diversification / Evolution → Decay / Transfer`

### Axis C — Domain

Economic, monetary, epistemic, semantic, informational, reputational, attention, network, technical, infrastructural, administrative, operational, political, constitutional, symbolic, brand, cognitive, mnemonic, property, territorial, allocation, certification, and others.

This prevents statements such as “X has more power than Y” from being treated as meaningful without specifying **what kind of resource, what puissance, what relation, through what mechanism, over whom, in what domain, for how long, and with what counterpowers**.

## kOA as the primary systems case

kOA is analyzed as a **power ecology**: a system of systems intended to transform dispersed resources into cumulative collective capability through:

> **Know → Choose → Act → Remember → Know better**

Each component is analyzed twice:

1. **What puissance does it create or amplify?**
2. **What power relations can arise around that puissance?**

Examples:

- **Kristal** can create epistemic and mnemonic puissance; authority registries, validation rules, reader policies, and canonization can create epistemic or standard-setting power relations.
- **Konnaxion** can create associative, communicative, and discoverability puissance; ranking, moderation, routing, and access can create visibility or agenda power.
- **Koali / EkoH** can make competence and contribution more legible and mobilizable; credibility signals can create recognition and opportunity power.
- **SmartVote** can create comparative judgment puissance; lenses, defaults, discoverability, and weighting rules can create agenda or advisory influence.
- **Orgo** can create operational puissance; assignment, escalation, routing, timing, and closure rules can create administrative power.
- **Capsules / federation** can reduce terminal dependency by making substitution, local operation, and branch formation more effective.

The repository does **not** assume that competence, ethics, credibility, truth, legitimacy, or branch quality can be measured perfectly. Consequential readings must remain attributable, scoped, contestable, revisable, and comparable.

## Constitutional orientation

> **Strong distributed puissance. Weak and non-terminal sovereignty.**
>
> **Composition without automatic conversion.**
>
> **Plurality without fragmentation.**
>
> **Stable interoperability. Evolving branches.**
>
> **Improvement without final authority.**

The central constitutional problem is not how to eliminate all power. It is how to create enormous distributed capability while preventing useful functional puissance from silently converting into arbitrary, cross-domain, or terminal power.

## Repository map

- [`framework/`](framework/) — field definition, ontology, effective possibility, three-axis model, power ecology, pre-political mediation, and constitutional thesis.
- [`dynamics/`](dynamics/) — formation, mobilization, composition, conversion, returns, compounding, concentration, capture, counterpower, diversification, decay, transfer.
- [`resources/`](resources/) — accumulated stocks and conditions that can support future capacity.
- [`puissance/`](puissance/) — families of effective mobilizable capacity.
- [`relations/`](relations/) — mechanisms through which puissance becomes relational power.
- [`domains/`](domains/) — the substantive domains in which resources, puissance, and power relations operate.
- [`constitution/`](constitution/) — non-domination, scope, firewalls, counterpowers, revocability, exit, federation, and non-terminal architecture.
- [`branch-ecology/`](branch-ecology/) — competing Kristals, complementarity, lineage, dominance, branch mobility, recombination, and evolutionary governance.
- [`koa/`](koa/) — kOA analyzed using the full framework.
- [`assessment/`](assessment/) — qualitative and machine-readable methods for system analysis.
- [`cases/`](cases/) — applied analyses and legacy stress tests.
- [`schemas/`](schemas/) — YAML schemas for ontology, relations, returns, branches, authority, conversions, and system profiles.
- [`history/`](history/) — genealogy of the theory across the supplied corpus.
- [`research/`](research/) — disciplinary map and literature roadmap.
- [`sources/`](sources/) — corpus provenance, epistemic status, concept origins, and technical-evidence gaps.

## Epistemic discipline

Every substantive document uses two independent labels:

- **maturity** — `CURRENT-CORE`, `CURRENT-EXPERIMENTAL`, `OPEN-QUESTION`, `LEGACY-PROPOSAL`, etc.;
- **claim_type** — `SOURCE-DERIVED`, `ANALYTICAL-RECONSTRUCTION`, `NEW-CONCEPT`, or `EXTERNAL-RESEARCH`.

The supplied corpus is the basis of the repository, but the formal ontology and several analytical concepts are reconstructions developed from the corpus and the Power Dynamics work. The repo therefore distinguishes source-derived claims from later synthesis rather than silently treating all terminology as original source language.
