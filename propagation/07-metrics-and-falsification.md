---
maturity: "CURRENT-CORE"
claim_type: "ANALYTICAL-RECONSTRUCTION"
scope: "GENERAL"
version: "6.3"
title: "Propagation Metrics and Falsification"
source_basis:
  - S21
  - S25
  - S29
---
# Propagation Metrics and Falsification

Propagation should be measured as a set of transitions, not asserted from architecture alone.

## Activation metrics

- time to first locally useful state;
- time from first exposure to qualified examination;
- World / demo → evaluator conversion;
- evaluator → bounded pilot conversion;
- pilot → deployment conversion;
- deployment → repeated use;
- deployment → referral / routing to another organization.

## Replication metrics

- installation time for a non-founder operator;
- founder minutes required per new instance;
- restore / migration time;
- time to second independent instance;
- percentage of deployments completed without founder intervention;
- number of operators able to train another operator.

## Cross-branch metrics

- percentage of revenue reinvested into shared capability;
- number of branches consuming an asset produced by another branch;
- reuse count per internal tool / integration / template;
- credibility spillover: one branch's validated result leading to qualified review of another;
- integration reuse across domains.

## Network / discovery metrics

- number of objects evaluable by SmartVote;
- number of active domains with meaningful expertise data;
- ranking usefulness / downstream selection quality;
- percentage of high-ranked items later reused, funded, taught, or deployed;
- disagreement between baseline and advisory lenses and how users interpret it.

## Multilingual metrics

- languages by conformance tier;
- test coverage per language;
- native-review status;
- population / institutions actually reached, not merely nominal language count;
- contribution rate from newly supported language communities.

## Independence metrics

- founder intervention per month / deployment / governance cycle;
- number of maintainers with release capability;
- number of independently operated instances;
- number of successful exits / migrations / forks;
- proportion of core decisions reproducible from public rules rather than private interpretation.

## Falsification examples

A proposed propagation loop is weakened when:

- demonstrations generate views but not examinations;
- examinations generate no pilots;
- pilots require permanent founder operation;
- revenue does not reduce future deployment cost;
- integrations increase maintenance faster than utility;
- more SmartVote data decreases decision quality or increases gaming;
- language count rises while usable quality or adoption does not;
- federation increases dependency on one central service;
- documentation volume increases due-diligence time.

The objective is to discover **which loops actually close in practice**.
