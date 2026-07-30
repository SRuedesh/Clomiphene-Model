### In vitro and physicochemical data

Drug-dependent parameters for (E)-clomiphene and its metabolites were taken from the published PBPK model and its supplement ([Kovar 2022](#5)). [Table 1](#table-1) gives the physicochemical, distribution, absorption, metabolism, and elimination parameters used in the final model. The Source column identifies the original literature or database named in Supplement Tables S4-S7. It identifies model-fitted and assumed values directly.

| Parameter | Unit | Value | Source | Description |
| --- | ---: | ---: | --- | --- |
| **(E)-Clomiphene** |  |  |  |  |
| MW | g/mol | 405.96 | [Siramshetty 2022](#5) | Molecular weight. |
| pK<sub>a</sub>,base | - | 9.31 | [ChemAxon 2009](#5) | pKa of a basic ionization site. |
| Solubility | mg/mL | 0.0138 | [Das 2020](#5) | Aqueous solubility at pH 6.8. |
| logP | - | 5.67 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 0.08 | Optimized | Fraction unbound in plasma. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.13 | [Kröner 2018](#5) | Michaelis constant for formation of (E)-4-hydroxyclomiphene from (E)-clomiphene. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.03 | [Kröner 2018](#5) | Michaelis constant for formation of other metabolite from (E)-clomiphene. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.78 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of (E)-N-desethylclomiphene from (E)-clomiphene. |
| K<sub>m,CYP3A4</sub> | µmol/L | 0.78 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of (E)-N-desethylclomiphene from (E)-clomiphene. |
| k<sub>cat,CYP3A4</sub> | 1/min | 45.0 | Optimized | Catalytic rate constant for formation of (E)-N-desethylclomiphene from (E)-clomiphene. |
| K<sub>m,CYP2B6</sub> | µmol/L | 0.60 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of (E)-4-hydroxyclomiphene from (E)-clomiphene. |
| k<sub>cat,CYP2B6</sub> | 1/min | 7.5 | Optimized | Catalytic rate constant for formation of (E)-4-hydroxyclomiphene from (E)-clomiphene. |
| GFR fraction | - | 0.92 | Optimized | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1.00 | Assumed | Fraction released continuously into bile. |
| Partition coefficients | - | Schmitt | [Schmitt 2008](#5) | Tissue-to-plasma partition coefficients calculated with the Schmitt method. |
| Cellular permeabilities | - | Charge-dependent Schmitt | [Kawai 1994](#5) | Cellular permeabilities calculated with the charge-dependent Schmitt method. |
| P<sub>int</sub> | cm/min | 0.08 | Optimized | Specific transcellular intestinal permeability. |
| t<sub>50</sub> | min | 6.80 | Assumed | Time to dissolve 50% of the dose. |
| Weibull shape | - | 0.47 | Assumed | Shape parameter of the Weibull dissolution function. |
| **(E)-N-desethylclomiphene** |  |  |  |  |
| MW | g/mol | 377.91 | [ChemAxon 2009](#5) | Molecular weight. |
| pK<sub>a</sub>,base | - | 8.14 | Optimized | pKa of a basic ionization site. |
| Solubility | mg/mL | 0.46 | [ChemAxon 2009](#5) | Aqueous solubility at pH 6.5. |
| logP | - | 4.17 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 0.86 | Optimized | Fraction unbound in plasma. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.49 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of (E)-4-hydroxy-N-desethylclomiphene from (E)-N-desethylclomiphene. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.97 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of other metabolite from (E)-N-desethylclomiphene. |
| K<sub>m,CYP3A4</sub> | µmol/L | 0.97 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of other metabolite from (E)-N-desethylclomiphene. |
| k<sub>cat,CYP3A4</sub> | 1/min | 0.8 | Optimized | Catalytic rate constant for formation of other metabolite from (E)-N-desethylclomiphene. |
| GFR fraction | - | 0.10 | Optimized | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1.00 | Assumed | Fraction released continuously into bile. |
| Partition coefficients | - | Rodgers and Rowland | [Rodgers 2005](#5); [Rodgers 2006](#5) | Tissue-to-plasma partition coefficients calculated with the Rodgers and Rowland method. |
| Cellular permeabilities | - | Charge-dependent Schmitt | [Kawai 1994](#5) | Cellular permeabilities calculated with the charge-dependent Schmitt method. |
| **(E)-4-hydroxyclomiphene** |  |  |  |  |
| MW | g/mol | 421.97 | [ChemAxon 2009](#5) | Molecular weight. |
| pK<sub>a</sub>,acid | - | 8.64 | [ChemAxon 2009](#5) | pKa of an acidic ionization site. |
| pK<sub>a</sub>,base | - | 7.90 | Optimized | pKa of a basic ionization site. |
| Solubility | mg/mL | 0.06 | [ChemAxon 2009](#5) | Aqueous solubility at pH 6.5. |
| logP | - | 5.50 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 0.45 | Optimized | Fraction unbound in plasma. |
| K<sub>m,CYP2D6</sub> | µmol/L | 3.60 | [Kröner 2018](#5) | Michaelis constant for formation of other metabolite from (E)-4-hydroxyclomiphene. |
| K<sub>m,CYP3A4</sub> | µmol/L | 3.40 | [Mürdter 2012](#5); [Ganchev 2014](#5) | Michaelis constant for formation of (E)-4-hydroxy-N-desethylclomiphene from (E)-4-hydroxyclomiphene. |
| k<sub>cat,CYP3A4</sub> | 1/min | 19.5 | Optimized | Catalytic rate constant for formation of (E)-4-hydroxy-N-desethylclomiphene from (E)-4-hydroxyclomiphene. |
| CL<sub>hep</sub> | 1/min | 23.78 | Optimized | Unspecific hepatic clearance. |
| GFR fraction | - | 0.24 | Optimized | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1.00 | Assumed | Fraction released continuously into bile. |
| Partition coefficients | - | Berezhkovskiy | [Berezhkovskiy 2004](#5) | Tissue-to-plasma partition coefficients calculated with the Berezhkovskiy method. |
| Cellular permeabilities | cm/min | 2.23 | [OSP Suite Manual 2021](#5) | Calculated cellular permeability. |
| **(E)-4-hydroxy-N-desethylclomiphene** |  |  |  |  |
| MW | g/mol | 393.91 | [ChemAxon 2009](#5) | Molecular weight. |
| pK<sub>a</sub>,acid | - | 8.69 | [ChemAxon 2009](#5) | pKa of an acidic ionization site. |
| pK<sub>a</sub>,base | - | 9.65 | [ChemAxon 2009](#5) | pKa of a basic ionization site. |
| Solubility | mg/mL | 0.17 | [ChemAxon 2009](#5) | Aqueous solubility at pH 6.5. |
| logP | - | 3.71 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 1.32 | [Watanabe 2018](#5) | Fraction unbound in plasma. |
| K<sub>m,CYP2D6</sub> | µmol/L | 8.86 | Assumed | Michaelis constant for formation of other metabolite from (E)-4-hydroxy-N-desethylclomiphene. |
| CL<sub>hep</sub> | 1/min | 8.50 | Optimized | Unspecific hepatic clearance. |
| GFR fraction | - | 0.13 | Optimized | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1.00 | Assumed | Fraction released continuously into bile. |
| Partition coefficients | - | Schmitt | [Schmitt 2008](#5) | Tissue-to-plasma partition coefficients calculated with the Schmitt method. |
| Cellular permeabilities | - | Charge-dependent Schmitt | [Kawai 1994](#5) | Cellular permeabilities calculated with the charge-dependent Schmitt method. |

**Table 1:**<a name="table-1"></a> Drug-dependent parameters used in the final clomiphene model. Original sources are those assigned in Supplement Tables S4-S7 of [Kovar 2022](#5).

<sup>e</sup> Other metabolite: an undefined downstream product represented as an elimination pathway in the model.

The CYP2D6 activity-score-specific catalytic rates are listed in [Table 1a](#table-1a).

| Substrate | Product or pathway | AS = 0 | AS = 0.5 | AS = 0.75 | AS = 1 | AS = 2 | AS = 3 | Unit |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| (E)-Clomiphene | (E)-4-hydroxyclomiphene | 0 | 57.48 | 81.57 | 175.08 | 306.38 | 467.23 | 1/min |
| (E)-Clomiphene | (E)-N-desethylclomiphene | 0 | 21.12 | 27.78 | 61.56 | 121.36 | 171.54 | 1/min |
| (E)-Clomiphene | Other CYP2D6 hydroxylation | 0 | 22.68 | 29.84 | 66.13 | 130.35 | 184.25 | 1/min |
| (E)-N-desethylclomiphene | (E)-4-hydroxy-N-desethylclomiphene | 0 | 10.35 | 12.37 | 28.59 | 64.52 | 84.01 | 1/min |
| (E)-N-desethylclomiphene | Other CYP2D6 desethylation | 0 | 1.02 | 1.34 | 2.96 | 5.84 | 8.25 | 1/min |
| (E)-4-hydroxyclomiphene | Other CYP2D6 elimination | 0 | 148.80 | 195.78 | 433.82 | 855.17 | 1208.79 | 1/min |
| (E)-4-hydroxy-N-desethylclomiphene | Other CYP2D6 elimination | 0 | 36.84 | 48.47 | 107.40 | 211.71 | 299.26 | 1/min |

**Table 1a:**<a name="table-1a"></a> CYP2D6 activity-score-specific k<sub>cat</sub> values. AS = 2 values were optimized. AS = 0 values were assumed to be zero. Other values were calculated from AS = 2 with the pathway-specific *in vitro* scaling factors in Supplement Table S8 of [Kovar 2022](#5). AS: activity score.

External studies did not report CYP2D6 activity scores or phenotypes. The model used the study-specific optimized CYP2D6 catalytic rates in [Table 1b](#table-1b).

| Study profile | (E)-Clomiphene to (E)-4-hydroxyclomiphene | (E)-Clomiphene to other metabolite | (E)-Clomiphene to (E)-N-desethylclomiphene | Unit |
| --- | ---: | ---: | ---: | --- |
| Mikkelson 1986 | 213.0 | 90.6 | 84.4 | 1/min |
| Miller 2019 | 18.1 | 7.7 | 7.2 | 1/min |
| Ratiopharm GmbH 2016 | 283.1 | 120.5 | 112.1 | 1/min |
| Wiehle 2013, 6.25 mg | 87.7 | 37.3 | 34.8 | 1/min |
| Wiehle 2013, 12.5 mg | 124.1 | 52.8 | 49.1 | 1/min |
| Wiehle 2013, 25 mg | 43.3 | 18.4 | 17.1 | 1/min |

**Table 1b:**<a name="table-1b"></a> Study-specific optimized CYP2D6 k<sub>cat</sub> values for the external clinical profiles, as reported in Supplement Table S1 of [Kovar 2022](#5).

### Clinical data

The evaluation includes 12 plasma concentration-time profiles after oral clomiphene or enclomiphene administration ([Table 2](#table-2)). Six activity-score groups from the Mürdter 2016 panel were used for model building. Six external profiles were used for model verification.

| Source | Dose [mg] / schedule\* | Age [years] | Weight [kg] | Sex | N | Form. | CYP2D6 characterization |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| [Mikkelson 1986](#5) | 50 clomiphene citrate (21 (E)-clomiphene model dose), oral | 32 | 62.4 | Female | 23 | Tablet | Study-specific CYP2D6 k<sub>cat</sub> |
| [Miller 2019](#5) | 50 clomiphene citrate (21 (E)-clomiphene model dose), oral, multiple dose | 31.5 ± 3.6 | 77.9 ± 8.2 | Male | 12 | Tablet | Study-specific CYP2D6 k<sub>cat</sub> |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 25.2 (22–29) | 62.3 (50–70) | Female | 6 | Tablet | AS = 0 (PM) |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 24.3 (21–30) | 59.3 (55.5–64) | Female | 4 | Tablet | AS = 0.5 (IM) |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 22 | 63 | Female | 1 | Tablet | AS = 0.75 (IM) |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 25.5 (23–28) | 68.8 (63.5–74) | Female | 2 | Tablet | AS = 1 (IM) |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 32.3 (26–43) | 56.5 (48–63.5) | Female | 3 | Tablet | AS = 2 (NM) |
| [Mürdter 2016](#5)<sup>+</sup> | 100 clomiphene citrate (42 (E)-clomiphene model dose), oral | 25.7 (22–28) | 61.7 (54–73) | Female | 3 | Tablet | AS = 3 (UM) |
| [Ratiopharm GmbH 2016](#5) | 50 clomiphene citrate (21 (E)-clomiphene model dose), oral | NR | NR | NR | 18 | Tablet | Study-specific CYP2D6 k<sub>cat</sub> |
| [Wiehle 2013](#5) | 6.25 enclomiphene citrate, oral, multiple dose | 53.3 ± 10.2 | NR | Male | 16 | Capsule | Study-specific CYP2D6 k<sub>cat</sub> |
| [Wiehle 2013](#5) | 12.5 enclomiphene citrate, oral, multiple dose | 53.3 ± 10.2 | NR | Male | 14 | Capsule | Study-specific CYP2D6 k<sub>cat</sub> |
| [Wiehle 2013](#5) | 25 enclomiphene citrate, oral, multiple dose | 53.3 ± 10.2 | NR | Male | 16 | Capsule | Study-specific CYP2D6 k<sub>cat</sub> |

**Table 2:**<a name="table-2"></a> Clinical (E)-clomiphene concentration-time profiles used for model building and verification. Data for the external studies are from Supplement Table S2 of [Kovar 2022](#5). The model-dose equivalents identify the evaluated simulation dose. \*: Single oral dose unless otherwise specified. AS: activity score. IM: intermediate metabolizer. NM: normal metabolizer. NR: not reported. PM: poor metabolizer. PT: predicted phenotype. UM: ultrarapid metabolizer. <sup>+</sup>: data used for model building. Parenthetical PTs for AS-coded rows use the CYP2D6 activity score-to-phenotype mapping from [Moore 2026](#5). Study-specific CYP2D6 k<sub>cat</sub>: activity score and phenotype were not reported, and the study-specific optimized values in Table 1b were used.
