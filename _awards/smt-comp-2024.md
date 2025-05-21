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
  divisions:
  - division: BitVec
  - division: Equality+MachineArith
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-single-query/
  - division: FPArith
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-single-query/
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-single-query/
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-single-query/
- track: incremental
  name: Incremental Track
  divisions:
  - division: BitVec
  - division: Equality+MachineArith
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-incremental/
  - division: FPArith
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-incremental/
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-incremental/
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-incremental/
- track: unsat-core
  name: Unsat Core Track
  divisions:
  - division: Bitvec
  - division: Equality+MachineArith
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-unsat-core/
  - division: FPArith
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-unsat-core/
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-unsat-core/
  - division: QF_FPArith
- track: model-validation
  name: Model Validation Track
  divisions:
  - division: QF_ADT+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_adt_bitvec-model-validation/
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-model-validation/
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-model-validation/
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-model-validation/

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
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-single-query/
    place: 1
    awards: sequential, parallel, unsat, 24s
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-single-query/
    place: 1
    awards: sequential, parallel, sat, unsat
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-single-query/
    place: 1
    awards: sequential, parallel, sat, unsat, 24s
  mentions:
  - division: Equality+MachineArith
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-single-query/
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
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-incremental/
    place: 1
    awards: parallel, 24s
  - division: FPArith
    place: 1
    awards: parallel
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-incremental/
    place: 1
    awards: parallel
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-incremental/
    place: 1
    awards: parallel
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-incremental/
    place: 1
    awards: parallel, 24s

- track: unsat-core
  name: Unsat Core Track
  medals:
  - division: FPArith
    place: 1
    awards: sequential, parallel, unsat, 24s
  - division: QF_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_bitvec-unsat-core/
    place: 1
    awards: sequential, parallel, unsat
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-unsat-core/
    place: 1
    awards: sequential, parallel, unsat, 24s
  mentions:
  - division: Equality+MachineArith
    division_url: https://smt-comp.github.io/2024/results/equality_machinearith-unsat-core/
    logics:
    - name: AUFBV
      place: 1
      awards: sequential, parallel, unsat
  - division: QF_Equality+Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_equality_bitvec-unsat-core/
    logics:
    - name: QF_ABV
      logic_url: https://smt-comp.github.io/2024/results/qf_abv-unsat-core/
      place: 1
      awards: sequential, parallel, unsat, 24s
    - name: QF_AUFBV
      logic_url: https://smt-comp.github.io/2024/results/qf_aufbv-unsat-core/
      place: 1
      awards: 24s

- track: model-validation
  name: Model Validation Track
  medals:
  - division: QF_ADT_Bitvec
    division_url: https://smt-comp.github.io/2024/results/qf_adt_bitvec-model-validation/
    place: 1
    awards: sequential, parallel, sat, 24s
  mentions:
  - division: QF_FPArith
    division_url: https://smt-comp.github.io/2024/results/qf_fparith-model-validation/
    logics:
    - name: QF_ABVFP
      logic_url: https://smt-comp.github.io/2024/results/qf_abvfp-model-validation/
      place: 1
      awards: sequential, parallel, sat, 24s
    - name: QF_BVFP
      logic_url: https://smt-comp.github.io/2024/results/qf_bvfp-model-validation/
      place: 1
      awards: 24s
    - name: QF_BVFPLRA
      logic_url: https://smt-comp.github.io/2024/results/qf_bvfplra-model-validation/
      place: 1
      awards: sequential, parallel, sat, 24s
    - name: QF_FP
      logic_url: https://smt-comp.github.io/2024/results/qf_fp-model-validation/
      place: 1
      awards: 24s
    - name: QF_FPLRA
      logic_url: https://smt-comp.github.io/2024/results/qf_fplra-model-validation/
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
