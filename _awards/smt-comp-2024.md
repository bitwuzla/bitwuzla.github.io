---
layout: awards 

event: SMT-COMP 2024
event_url: https://smt-comp.github.io/2024

version:
binary: https://zenodo.org/records/11754739
sysdesc-title: Bitwuzla at the SMT-COMP 2024
sysdesc-url: /data/smtcomp2024/paper.pdf

entered:

- track: single-query
  name: Single Query Track
  divisions: BitVec, Equality+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: incremental
  name: Incremental Track
  divisions: BitVec, Equality+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: unsat-core
  name: Unsat Core Track
  divisions: Bitvec, Equality+MachineArith, FPArith, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith
- track: model-validation
  name: Model Validation Track
  divisions: QF_ADT+Bitvec, QF_Bitvec, QF_Equality+Bitvec, QF_FPArith

tracks:

- track: single-query
  name: Single Query Track
  medals:
  - division: Bitvec
    place: 1
    awards: sat
  - division: FPArith
    place: 1
    awards: sequential, parallel, sat, unsat, 24s
  - division: QF_Bitvec
    place: 1
    awards: sequential, parallel, unsat, 24s
  - division: QF_Equality+Bitvec
    place: 1
    awards: sequential, parallel, sat, unsat
  - division: QF_FPArith
    place: 1
    awards: sequential, parallel, sat, unsat, 24s
  mentions:
  - division: Equality+MachineArith
    logics:
    - name: ABVFP
      place: 1
      awards: sat
    - name: AUFBV
      place: 1
      awards: sequential, parallel, sat, unsat, 24s
    - name: AUFBVFP
      place: 1
      awards: sequential, parallel, sat, unsat, 24s
    - name: UFBV
      place: 1
      awards: 24s

- track: incremental
  name: Incremental Track
  medals:
  - division: BitVec
    place: 1
    awards: 24s
  - division: Equality+MachineArith
    place: 1
    awards: parallel, 24s
  - division: FPArith
    place: 1
    awards: parallel
  - division: QF_Bitvec
    place: 1
    awards: parallel
  - division: QF_Equality+Bitvec
    place: 1
    awards: parallel
  - division: QF_FPArith
    place: 1
    awards: parallel, 24s

- track: unsat-core
  name: Unsat Core Track
  medals:
  - division: FPArith
    place: 1
    awards: sequential, parallel, unsat, 24s
  - division: QF_Bitvec
    place: 1
    awards: sequential, parallel, unsat
  - division: QF_FPArith
    place: 1
    awards: sequential, parallel, unsat, 24s
  mentions:
  - division: Equality+MachineArith
    logics:
    - name: AUFBV
      place: 1
      awards: sequential, parallel, unsat
  - division: QF_Equality+Bitvec
    logics:
    - name: QF_ABV
      place: 1
      awards: sequential, parallel, unsat, 24s
    - name: QF_AUFBV
      place: 1
      awards: 24s

- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_ADT_Bitvec
    place: 1
    awards: sequential, parallel, sat, 24s
  mentions:
  - division: QF_FPArith
    logics:
    - name: QF_ABVFP
      place: 1
      awards: sequential, parallel, sat, 24s
    - name: QF_BVFP
      place: 1
      awards: 24s
    - name: QF_BVFPLRA
      place: 1
      awards: sequential, parallel, sat, 24s
    - name: QF_FP
      place: 1
      awards: 24s
    - name: QF_FPLRA
      place: 1
      awards: sequential, parallel, sat, 24s

overall:

- award: biggest-lead
  name: Biggest Lead
  tracks:
  - track: incremental
    name: Incremental Track
    place: 1
    awards: parallel
  - track: incremental
    name: Incremental Track
    place: 3
    awards: 24s
  - track: unsat-core
    name: Unsat Core Track
    place: 3
    awards: sequential, parallel, unsat
  - track: single-query
    name: Single Query Track
    place: 3
    awards: sat, unsat

- award: largest-contribution
  name: Largest Contribution
  tracks:
  - track: incremental
    name: Incremental Track
    place: 2
    awards: parallel
  - track: incremental
    name: Incremental Track
    place: 3
    awards: 24s
  - track: model-validation
    name: Model Validation Track
    place: 2
    awards: 24s
  - track: model-validation
    name: Model Validation Track
    place: 3
    awards: sequential, parallel, sat
  - track: unsat-core
    name: Unsat Core Track
    place: 2
    awards: 24s
  - track: unsat-core
    name: Unsat Core Track
    place: 3
    awards: sequential, parallel, unsat
  - track: single-query
    name: Single Query Track
    place: 3
    awards: sequential, parallel

---
