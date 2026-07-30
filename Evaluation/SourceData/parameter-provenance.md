# Parameter provenance

This record links the clomiphene evaluation report to the local copy of the Kovar 2022 supplement, `pharmaceutics-2020207-supplementary.pdf`.

## Coverage

| Supplement location | Report location | Snapshot coverage | Review classification |
| --- | --- | --- | --- |
| Table S1, PDF p. 3 | Table 1b | Three CYP2D6 k<sub>cat</sub> paths for each of six external profiles | Documented optimization |
| Table S4, PDF p. 8 | Table 1, (E)-clomiphene | Physicochemical, binding, permeability, filtration, CYP2B6, CYP2D6, CYP3A4, and tablet-dissolution values | Exact match, unit-converted match, assumed, or documented optimization |
| Table S5, PDF p. 9 | Table 1, (E)-N-desethylclomiphene | Physicochemical, binding, filtration, CYP2D6, and CYP3A4 values | Exact match, assumed, or documented optimization |
| Table S6, PDF p. 10 | Table 1, (E)-4-hydroxyclomiphene | Physicochemical, binding, filtration, hepatic clearance, CYP2D6, CYP3A4, and cellular-permeability values | Exact match or documented optimization |
| Table S7, PDF p. 11 | Table 1, (E)-4-hydroxy-N-desethylclomiphene | Physicochemical, binding, filtration, hepatic clearance, and CYP2D6 values | Exact match, unit-converted match, assumed, or documented optimization |
| Table S8, PDF p. 13 | Table 1a | Seven CYP2D6 pathways across activity scores 0, 0.5, 0.75, 1, 2, and 3 | AS = 2 optimized, AS = 0 assumed, other activity scores calculated |

The auditable path-level records are in `../../../../CYP2D6-report-review/reviews/source-parameter-table-mappings.csv`. The local review pipeline writes the resolved snapshot values and comparison results to `../review/table-to-snapshot-comparison.csv`.

## Structured snapshot fields

The review pipeline enumerates named numerical parameters. The following supplement-defined fields use other JSON structures and are verified separately.

| Compound | Field | Supplement value | Snapshot field | Status |
| --- | --- | --- | --- | --- |
| (E)-clomiphene | pK<sub>a</sub> | 9.31, basic | `PkaTypes: Base = 9.31` | Exact match |
| (E)-clomiphene | Partition method | Schmitt | `CalculationMethods` | Exact match |
| (E)-clomiphene | Cellular permeability method | Charge-dependent Schmitt | `CalculationMethods` | Exact match |
| (E)-N-desethylclomiphene | pK<sub>a</sub> | 8.14, basic, optimized | `PkaTypes: Base = 8.14` | Documented optimization |
| (E)-N-desethylclomiphene | Partition method | Rodgers and Rowland | `CalculationMethods` | Exact match |
| (E)-N-desethylclomiphene | Cellular permeability method | Charge-dependent Schmitt | `CalculationMethods` | Exact match |
| (E)-4-hydroxyclomiphene | pK<sub>a</sub> | 8.64, acidic | `PkaTypes: Acid = 8.64` | Exact match |
| (E)-4-hydroxyclomiphene | pK<sub>a</sub> | 7.90, basic, optimized | `PkaTypes: Base = 7.90000492397066` | Documented optimization |
| (E)-4-hydroxyclomiphene | Partition method | Berezhkovskiy | `CalculationMethods` | Exact match |
| (E)-4-hydroxyclomiphene | Cellular permeability method | PK-Sim Standard | `CalculationMethods` | Exact match |
| (E)-4-hydroxy-N-desethylclomiphene | pK<sub>a</sub> | 8.69, acidic | `PkaTypes: Acid = 8.69` | Exact match |
| (E)-4-hydroxy-N-desethylclomiphene | pK<sub>a</sub> | 9.65, basic | `PkaTypes: Base = 9.65` | Exact match |
| (E)-4-hydroxy-N-desethylclomiphene | Partition method | Schmitt | `CalculationMethods` | Exact match |
| (E)-4-hydroxy-N-desethylclomiphene | Cellular permeability method | Charge-dependent Schmitt | `CalculationMethods` | Exact match |

All four compounds use a continuous enterohepatic-recirculation fraction of 1.00 as an explicit supplement assumption. This setting is not represented as a named numerical parameter in the exported snapshot JSON.
