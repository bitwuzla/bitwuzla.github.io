---
layout: awards
title: SMT-COMP 2021

event: SMT-COMP 2021
event_url: https://smt-comp.github.io/2021

version:
binary: https://www.starexec.org/starexec/secure/details/solver.jsp?id=33809
sysdesc-title: Bitwuzla at the SMT-COMP 2021
sysdesc-url:

entered:

- track: single-query
  name: Single Query Track
  divisions: QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: incremental
  name: Incremental Track
  divisions: QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: unsat-core
  name: Unsat Core Track
  divisions: QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: model-validation
  name: Model Validation Track
  divisions: QF_Bitvec, QF_Equality+Bitvec

tracks:

- track: single-query
  name: Single Query Track
  medals:
  - division: QF_Bitvec
    awards: sequential, parallel, sat, 24s
    place: 1
  - division: QF_Equality+Bitvec
    place: 1
  mentions:
  - division: QF_FPArith
    logics:
      - name:  QF_ABVFP
        place: 1
      - name: QF_BVFP
        place: 1
      - name: QF_BVFPLRA
        place: 1
      - name: QF_FP
        place: 1


- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_Bitvec
    place: 1

- track: unsat-core
  name: Unsat Core Track
  medals:
  - division: QF_Bitvec
    place: 1
  - division: QF_Equality+Bitvec
    place: 1
  - division: QF_FPArith
    place: 1

overall:

- award: biggest-lead
  name: Biggest Lead
  tracks:
  - track: model-validation
    name: Model Validation Track
    place: 3
  - track: unsat-core
    name: Unsat Core Track
    place: 3

- award: largest-contribution
  name: Largest Contribution
  tracks:
  - track: model-validation
    name: Model Validation Track
    place: 2

---
