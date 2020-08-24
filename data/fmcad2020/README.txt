==============================================================================
                                FMCAD'20

     Ternary Propagation-Based Local Searchfor more Bit-Precise Reasoning

                    Aina Niemetz and Mathias Preiner

==============================================================================

Experimental Data
-----------------

* prop_results.csv

  Data for comparison of base, propc, propc+, and propcb+ on all 14,382 QF_BV
  benchmarks with status "sat" with time limit 60 seconds.
  Each configuration was run with 20 different random seeds.

  The data taken for comparing base and propc in terms of
  moves/propagations/updates on commonly solved instances was from
  configurations prop-15 and propc-10.

  Note: The cluster log files are not included in this artifact due to the
  amount of data produced (100 cluster runs with 45G+ data). However, the
  provided CSV file includes all data (prop_results.csv) used in the paper.

* portfolio_results.csv

  Data for sequential portfolio runs for bb/bb-propcb+ with SAT solvers
  CaDiCal, CryptoMiniSat, Kissat and Lingeling.

* verify/

  Directory containing all 3575 verification benchmarks generated for all
  invertibility conditions and consistency conditions for bit-width 1-65 and
  the results from Bitwuzla, CVC4 and Z3 with a time limit of 3600 seconds.

* sygus/

  Directory containing the 30 SyGuS benchmarks used to synthesize (some) of the
  invertibility and consistency conditions (including the solver results from
  CVC4 and corresponding log files in the results directory).
