---
layout: awards 

event: SMT-COMP 2023
event_url: https://smt-comp.github.io/2023

version:
binary: https://www.starexec.org/starexec/secure/details/solver.jsp?id=44978
sysdesc-title: Bitwuzla at the SMT-COMP 2023
sysdesc-url: /data/smtcomp2023/paper.pdf

entered:

- track: single-query
  name: Single Query Track
  divisions: BitVec, Equality+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: incremental
  name: Incremental Track
  divisions: BitVec, Equality+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: unsat-core
  name: Unsat Core Track
  divisions: Bitvec, Equalit+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: model-validation
  name: Model Validation Track
  divisions: QF_ADT+Bitvec [exp], QF_Array+Bitvec_LinArith [exp], QF_Bitvec, QF_Equality+Bitvec, QF_FPArith

tracks:

- track: single-query
  name: Single Query Track
  medals:
  - division: Bitvec
    place: 1
    awards: sat, 24s
  - division: FPArith
    place: 1
  - division: QF_Equality+Bitvec
    place: 1
  - division: QF_FPArith
    place: 1
  mentions:
  - division: Equality+MachineArith
    logics:
      - name: ABVFP
        awards: sat, 24s
        place: 1
      - name: ABVFPLRA
        awards: 24s
        place: 1
      - name: AUFBV
        place: 1
      - name: AUFBVFP
        place: 1
      - name: UFBV
        place: 1
      - name: UFBV
        awards: sequential, parallel, unsat
        place: 1

- track: incremental
  name: Incremental Track
  medals:
  - division: Equality+MachineArith
    place: 1
  - division: FPArith
    place: 1
  - division: QF_Bitvec
    place: 1
  - division: QF_Equality+Bitvec
    place: 1
  - division: QF_FPArith
    place: 1

- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_Equality+Bitvec
    place: 1

- track: unsat-core
  name: Unsat Core Track
  medals:
  - division: FPArith
    place: 1
  mentions:
  - division: QF_FPArith
    logics:
      - name: QF_ABVFP
        place: 1
      - name: QF_ABVFPLRA
        place: 1
      - name: QF_BVFP
        place: 1
      - name: QF_BVFPLRA
        place: 1

overall:

- award: biggest-lead
  name: Biggest Lead
  tracks:
  - track: incremental
    name: Incremental Track
    place: 1
  - track: model-validation
    name: Model Validation Track
    place: 2
  - track: single-query
    name: Single Query Track
    awards: sequential, parallel, sat, unsat
    place: 2
  - track: unsat-core
    name: Unsat Core Track
    place: 3

- award: largest-contribution
  name: Largest Contribution
  tracks:
  - track: single-query
    name: Single Query Track
    awards: sat
    place: 2
  - track: single-query
    name: Single Query Track
    awards: sequential, parallel
    place: 3
  - track: incremental
    name: Incremental Track
    place: 3
  - track: unsat-core
    name: Unsat Core Track
    awards: sequential, parallel
    place: 3

---
