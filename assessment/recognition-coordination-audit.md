---
maturity: "CURRENT-CORE"
claim_type: "NEW-CONCEPT"
scope: "GENERAL"
version: "6.4"
title: "Recognition and Coordination Audit"
source_basis:
  - S01
  - S13
  - S15
  - S18
  - S25
  - S28
  - S30
---
# Recognition and Coordination Audit

Use this audit when a system makes people, claims, skills, contributions, or opportunities legible and then routes them into action.

## A. Recognition surface

1. What capacity, claim, contribution, conduct, or history is being recognized?
2. What evidence is used?
3. Who defines admissible evidence?
4. Who computes or interprets the recognition signal?
5. Is the signal domain-bounded and contextual?
6. Is the raw evidence inspectable where appropriate?
7. Can the person contest, correct, contextualize, or age out information?
8. Is the evidence portable to another operator or policy?
9. Can prestige, popularity, inherited status, affiliation, or incumbency substitute for evidence?
10. What access or opportunity changes because of the signal?

## B. Recognition wedge

Choose one bounded outcome `X` and state the counterfactual explicitly.

```text
W_recognition = X_calibrated-evidence - X_observed
```

Record separately:

- under-recognition;
- over-recognition;
- uncertainty;
- omitted evidence;
- proxy dependence;
- incumbent advantage;
- cost of contesting the reading.

Do not convert this into a universal human-worth score.

## C. Coordination surface

1. What need is being routed?
2. Which capacities are potentially relevant?
3. Which actors are actually reachable?
4. What availability constraints exist?
5. Is participation voluntary?
6. What confidentiality / privacy preferences apply?
7. What trust / reliability information is actually necessary?
8. What scheduling, geographic, legal, technical, or organizational constraints exist?
9. Who can override or close the match?
10. What happens when the system produces no match?

## D. Coordination wedge

Where output is comparable, estimate:

```text
W_coord = Y*_same-resources, lower-friction - Y_observed
```

Possible pilot measures:

- time from need to qualified responder;
- percentage of relevant internal knowledge found;
- task completion time;
- number of avoidable handoffs;
- duplicate work avoided;
- unused volunteer / expert hours activated;
- independent team-formation rate;
- resolution quality;
- rework / error rate;
- participant-reported burden;
- cost of coordination;
- founder / coordinator hours per activation.

## E. Credit / credibility conversion

If recognition affects financial access, record separately:

- evidence of competence / reliability;
- financial repayment evidence;
- income / cash flow;
- collateral;
- legal enforceability;
- pricing / interest terms;
- market conditions;
- institutional policy.

Do not infer financial creditworthiness from a general reputation signal or infer general human worth from financial creditworthiness.

## F. High-impact decisions

For finance, employment, education, health, public authority, access to children or vulnerable people, or other high-impact contexts, ask:

- Is a single score determinative?
- Is the decision authority legally / institutionally appropriate?
- Are criteria explicit?
- Is data minimized?
- Can relevant evidence be corrected?
- Is there recourse?
- Are protected rights independent of a general reputation score?
- Can a local or alternative policy be used?
- Is automated inference bounded?

## G. Power-over / power-to / power-with balance

Document whether the system changes:

```text
power to   → what can each participant do now?
power with → what can the group do together now?
power over → what new ability does an operator gain to condition others?
```

A successful pilot should not report only increased throughput. It should also report new dependencies and authority created by the improvement.

## H. Pilot result

A strong result documents both:

```text
capability gain
AND
non-terminal dependency
```

The core test is:

> **Did the system make useful capacity easier to recognize and coordinate while preserving contextuality, contestability, privacy, substitution, and exit?**
