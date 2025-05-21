---
layout: awards
title: SMT-COMP 2022

event: SMT-COMP 2022
event_url: https://smt-comp.github.io/2022

version:
binary: https://www.starexec.org/starexec/secure/details/solver.jsp?id=39101
sysdesc-title: Bitwuzla at the SMT-COMP 2022
sysdesc-url: /data/smtcomp2022/paper.pdf

entered:

- track: single-query
  name: Single Query Track
  divisions:
  - division: BitVec
  - division: Equality+MachineArith
  - division: FPArith
  - division: QF_Bitvec
  - division: QF_Equality+Bitvec
  - division: QF_FPArith
- track: incremental
  name: Incremental Track
  divisions:
  - division: BitVec
  - division: Equality+MachineArith
  - division: FPArith
  - division: QF_Bitvec
  - division: QF_Equality+Bitvec
  - division: QF_FPArith
- track: unsat-core
  name: Unsat Core Track
  divisions:
  - division: QF_Bitvec
  - division: QF_Equality+Bitvec
  - division: QF_FPArith
- track: model-validation
  name: Model Validation Track
  divisions:
  - division: QF_Bitvec
  - division: QF_Equality+Bitvec
  - division: QF_FPArith

tracks:

- track: single-query
  name: Single Query Track
  medals:
  - division: FPArith
    place: 1
  - division: QF_Bitvec
    awards: sequential, parallel, sat
    place: 1
  - division: QF_Equality+Bitvec
    place: 1
  - division: QF_FPArith
    place: 1

- track: incremental
  name: Incremental Track
  medals:
  - division: FPArith
    place: 1
  - division: QF_FPArith
    place: 1

- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_Bitvec
    place: 1
  - division: QF_Equality+Bitvec
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
  - track: single-query
    name: Single Query Track
    awards: sequential, parallel, sat
    place: 2
  - track: single-query
    name: Single Query Track
    awards: unsat
    place: 3

- award: largest-contribution
  name: Largest Contribution
  tracks:
  - track: single-query
    name: Single Query Track
    awards: sequential, parallel, sat
    place: 3
  - track: model-validation
    name: Model Validation Track
    place: 2
  - track: unsat-core
    name: Unsat Core Track
    place: 2


- name: FLoC'22 Olympic Games
  url: https://www.floc2022.org/floc-olympic-games
  medals:
  - medal: 1 silver medal

img: /img/floc22.jpg

---
