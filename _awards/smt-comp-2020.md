---
layout: awards
title: SMT-COMP 2020

event: SMT-COMP 2020
event_url: https://smt-comp.github.io/2020

version:
binary: https://www.starexec.org/starexec/secure/details/solver.jsp?id=29091
sysdesc-title: Bitwuzla at the SMT-COMP 2020
sysdesc-url: https://arxiv.org/abs/2006.01621

entered:

- track: single-query
  name: Single Query Track
  divisions: BV, QF_ABV,QF_ABVFP,QF_AUFBV,QF_BV,QF_BVFP,QF_FP,QF_UFBV,QF_UFFP
- track: incremental
  name: Incremental Track
  divisions: QF_ABV,QF_ABVFP,QF_AUFBV,QF_BV,QF_BVFP,QF_FP,QF_UFBV,QF_UFFP
- track: unsat-core
  name: Unsat Core Track
  divisions: QF_ABV,QF_ABVFP,QF_AUFBV,QF_BV,QF_BVFP,QF_FP,QF_UFBV,QF_UFFP
- track: model-validation
  name: Model Validation Track
  divisions: QF_BV


tracks:

- track: single-query
  name: Single Query Track
  medals:
  - division: QF_ABV
    place: 1
  - division: QF_ABVFP
    place: 1
  - division: QF_BV
    place: 1
  - division: QF_BVFP
    place: 1
  - division: QF_FP (sequential, parallel, sat, unsat)
    place: 1
  - division: QF_UFBV (24s)
    place: 1
  - division: QF_UFFP (24s)
    place: 1

- track: incremental
  name: Incremental Track
  medals:
  - division: QF_ABV
    place: 1
  - division: QF_ABVFP
    place: 1
  - division: QF_BVFP
    place: 1
  - division: QF_UFBV
    place: 1
  - division: QF_UFFP
    place: 1

- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_BV
    place: 1

- track: unsat-core
  name: Unsat Core Track
  medals:
  - division: QF_ABV
    place: 1
  - division: QF_ABVFP
    place: 1
  - division: QF_BV
    place: 1
  - division: QF_BVFP
    place: 1
  - division: QF_FP
    place: 1


overall:

- award: biggest-lead
  name: Biggest Lead
  tracks:
  - track: model-validation
    name: Model Validation Track (sequential, parallel)
    track_url: https://smt-comp.github.io/2020/results/biggest-lead-model-validation
    place: 1
  - track: incremental
    name: Incremental Track
    place: 3
  - track: unsat-core
    name: Unsat Core Track (sequential, parallel)
    place: 3

- award: largest-contribution
  name: Largest Contribution
  tracks:
  - track: model-validation
    name: Model Validation Track (sequential, parallel)
    place: 1
  - track: incremental
    name: Incremental Track
    place: 3
  - track: unsat-core
    name: Unsat Core Track (sequential, parallel)
    place: 3

---
