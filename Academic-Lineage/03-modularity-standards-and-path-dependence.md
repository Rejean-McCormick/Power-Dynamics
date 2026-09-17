---
maturity: "OPEN-QUESTION"
claim_type: "EXTERNAL-RESEARCH"
scope: "GENERAL"
version: "6.2"
title: "Modularity, Standards, Compatibility, and Path Dependence"
source_basis:
---
# Modularity, Standards, Compatibility, and Path Dependence

This lineage is central to the repo's attempt to combine **local freedom** with a **common compatible substrate**.

## Herbert Simon — near decomposability

Simon argued that complex systems often become tractable and evolvable when organized into subsystems with relatively strong internal interaction and weaker interaction across subsystem boundaries.

**Correspondence:** capsules, replaceable services, bounded modules, and the ambition to let parts of kOA evolve without requiring total-system redesign.

Reference: Herbert A. Simon, “The Architecture of Complexity,” *Proceedings of the American Philosophical Society* 106(6), 1962.

## Baldwin & Clark — modularity and visible design rules

Baldwin and Clark formalize modular systems in which components can change independently while obeying shared **design rules** / interfaces.

**Correspondence:**

> **Freeze only what is necessary for interoperability; allow everything else to mutate.**

This provides a strong academic parallel to kOA's intended combination of independent implementations, shared artifact contracts, and branch evolution.

Reference: Carliss Y. Baldwin and Kim B. Clark, *Design Rules, Volume 1: The Power of Modularity*, MIT Press, 2000. https://doi.org/10.7551/mitpress/2366.001.0001

## Interface power

The same modularity that creates freedom can create a new concentration point: **the interface itself**.

A party that controls the shared interface can shape all modules while appearing not to control them internally.

Power Dynamics should therefore treat shared interfaces as **governance surfaces**:

- Who can change the interface?
- Who bears migration cost?
- Can an older version remain viable?
- Can adapters bridge divergent versions?
- Can competing standards coexist?
- Who certifies compatibility?

## Farrell & Saloner — excess inertia

Farrell and Saloner analyze how the benefits of standardization can trap an industry in an inferior or obsolete standard under incomplete information — **excess inertia**.

**Correspondence:** a successful kOA compatibility layer could become difficult to change precisely because compatibility is valuable.

Reference: Joseph Farrell and Garth Saloner, “Standardization, Compatibility, and Innovation,” *RAND Journal of Economics* 16(1), 1985, pp. 70–83. https://doi.org/10.2307/2555589

## Katz & Shapiro — network externalities and installed-base power

Network goods become more valuable as more compatible users / complements exist. Adoption itself can therefore create structural advantage.

**New Power Dynamics concept proposed:** **Installed-Base Power** — the ability of an adopted protocol, implementation, or standard to constrain future choice because participants depend on continued interoperability.

Reference: Michael L. Katz and Carl Shapiro, “Network Externalities, Competition, and Compatibility,” *American Economic Review* 75(3), 1985, pp. 424–440. https://www.jstor.org/stable/1814809

## Paul Pierson — path dependence and increasing returns

Pierson describes how increasing returns can make timing and sequence matter, amplify initially small differences, and make established paths difficult to reverse.

**Correspondence:** early defaults, registries, naming conventions, scoring systems, reference implementations, and trust roots can become constitutionally significant long after they were introduced as convenience choices.

Reference: Paul Pierson, “Increasing Returns, Path Dependence, and the Study of Politics,” *American Political Science Review* 94(2), 2000, pp. 251–267. https://doi.org/10.2307/2586011

## Proposed constitutional invariant

> **Compatibility must not imply constitutional subordination.**

Related audit propositions:

- `Shared interface → explicit governance surface`;
- `Installed base → migration obligation`;
- `Compatibility benefit → ossification risk`;
- `Forkability without bridges → fragmentation risk`;
- `Version pluralism + adapters → evolutionary optionality`.

The academic literature establishes the failure modes. It does not prove that a particular kOA versioning or federation scheme solves them.
