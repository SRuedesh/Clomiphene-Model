### 2.3.1 Absorption

The model includes oral administration of (E)-clomiphene after clomiphene citrate or enclomiphene citrate dosing. The clinical panel study used clomiphene citrate tablets containing the E/Z isomer mixture, and the model evaluates the (E)-clomiphene fraction relevant to the measured parent-metabolite dataset [[1](References.md)].

Oral absorption is represented with a tablet Weibull dissolution function and compound intestinal permeability. The tablet formulation parameters describe the oral input profile, while differences between CYP2D6 activity-score groups are assigned to metabolism rather than absorption.

The external literature studies include single-dose and multiple-dose oral dosing conditions. These data support evaluation of oral input behavior across lower single doses and repeated enclomiphene exposure, but they do not by themselves resolve individual CYP2D6 activity in the absence of genotype or phenotype information.

### 2.3.2 Distribution

(E)-Clomiphene is represented as a highly lipophilic, highly protein-bound compound with logP of 5.67 and f<sub>u</sub> of 0.08% as summarized in [Section 2.2](Section2.2_Data.md). The metabolites are less lipophilic but remain substantially bound, with logP values of 4.17 for (E)-N-desethylclomiphene, 5.50 for (E)-4-hydroxyclomiphene and 3.71 for (E)-4-hydroxy-N-desethylclomiphene [[1](References.md)].

Partition coefficients were calculated with Schmitt, Rodgers and Rowland or Berezhkovskiy methods depending on the compound. The model therefore treats the parent and metabolites as separate distribution entities rather than as a single lumped active moiety.

The active hydroxylated metabolites are represented with their own molecular weight, pK<sub>a</sub>, lipophilicity, plasma binding and clearance parameters. This separation is required because metabolite exposure is controlled by both formation from upstream compounds and metabolite-specific elimination.

### 2.3.3 Metabolism and elimination

Clomiphene elimination is represented by CYP2D6-dependent hydroxylation and desethylation, CYP3A4-dependent desethylation and metabolite turnover, CYP2B6-dependent hydroxylation, renal filtration, enterohepatic recirculation and residual hepatic clearance components.

* CYP2D6

CYP2D6 is the central enzyme for DGI behavior in the model. It forms (E)-4-hydroxyclomiphene from (E)-clomiphene and contributes to desethylation and downstream metabolite elimination. Pathway-specific K<sub>m</sub> values are used, while k<sub>cat</sub> values depend on activity score [[1](References.md), [7](References.md)].

The CYP2D6 activity-score implementation is the key determinant of simulated exposure differences across poor, intermediate, normal and ultrarapid metabolizer groups. Poor-metabolizer activity is set to zero, while non-zero activity-score groups use scaled k<sub>cat</sub> values.

* CYP3A4, CYP2B6 and residual clearance

CYP3A4 is implemented for (E)-N-desethylclomiphene formation and downstream metabolite turnover. CYP2B6 contributes to (E)-4-hydroxyclomiphene formation from (E)-clomiphene. These pathways support non-CYP2D6 clearance and metabolite formation where the in vitro data indicate additional enzymatic contribution [[1](References.md), [9](References.md)].

Residual hepatic clearance terms are empirical. They should be interpreted as structural model components required to describe total disposition rather than as direct measurements of a single biochemical pathway.

* Renal filtration and enterohepatic recirculation

Renal filtration is included with compound-specific GFR fractions for the parent and metabolites. Enterohepatic recirculation is represented with continuous bile release fractions where required by the model structure.
