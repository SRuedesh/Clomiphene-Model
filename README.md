# Clomiphene-Model
Whole-body parent-metabolite PBPK model of (E)-clomiphene and its metabolites including CYP2D6 drug-gene interactions.

This repository contains the (E)-clomiphene model originally published by Kovar et al. [[1](#references)].

The model was developed and evaluated using clinical plasma pharmacokinetic data after oral clomiphene or enclomiphene administration by Kovar et al. [[1](#references)], Mikkelson et al. [[2](#references)], Ratiopharm GmbH [[3](#references)], Wiehle et al. [[4](#references)] and Miller et al. [[5](#references)].

Users of the model are expected to cite this study when using the model in scientific work, reports or derivative model development:
- [C Kovar, L Kovar, S Rüdesheim, D Selzer, B Ganchev, P Kröner, S Igel, R Kerb, E Schaeffeler, T E Mürdter, M Schwab, T Lehr. Prediction of Drug-Drug-Gene Interaction Scenarios of (E)-Clomiphene and Its Metabolites Using Physiologically Based Pharmacokinetic Modeling. Pharmaceutics, 2022;14:2604.](https://doi.org/10.3390/pharmaceutics14122604)

This clomiphene model is intended to describe (E)-clomiphene, (E)-N-desethylclomiphene, (E)-4-hydroxyclomiphene and (E)-4-hydroxy-N-desethylclomiphene pharmacokinetics across CYP2D6 activity-score groups.

The presented model includes the following features:

- oral administration of (E)-clomiphene,
- formation of (E)-N-desethylclomiphene, (E)-4-hydroxyclomiphene and (E)-4-hydroxy-N-desethylclomiphene,
- metabolism by CYP2D6, CYP3A4 and CYP2B6,
- enterohepatic recirculation,
- renal filtration and residual hepatic clearance,
- CYP2D6 activity score-dependent clearance.

## Repository files
This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation_plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found in the [latest release in this repository](https://github.com/Open-Systems-Pharmacology/Clomiphene-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found in the [latest OSP PBPK Model Library release](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] [C Kovar, L Kovar, S Rüdesheim, D Selzer, B Ganchev, P Kröner, S Igel, R Kerb, E Schaeffeler, T E Mürdter, M Schwab, T Lehr. Prediction of Drug-Drug-Gene Interaction Scenarios of (E)-Clomiphene and Its Metabolites Using Physiologically Based Pharmacokinetic Modeling. Pharmaceutics, 2022;14:2604.](https://doi.org/10.3390/pharmaceutics14122604)

[2] [T J Mikkelson, P D Kroboth, W J Cameron, L W Dittert, V Chungi, P J Manberg. Single-dose pharmacokinetics of clomiphene citrate in normal volunteers. Fertil Steril, 1986;46:392-396.](https://doi.org/10.1016/S0015-0282(16)49574-9)

[3] [Ratiopharm GmbH. Clomifen-ratiopharm 50 mg Tabletten, Fachinformation, 2016.](https://www.ratiopharm.de/produkte/details/praeparate/praeparatedaten/detail/pzn3884844.html)

[4] [R Wiehle, G R Cunningham, N Pitteloud, J Wike, K Hsu, G K Fontenot, M Rosner, A Dwyer, J Podolski. Testosterone Restoration by Enclomiphene Citrate in Men with Secondary Hypogonadism: Pharmacodynamics and Pharmacokinetics. BJU Int, 2013;112:1188-1200.](https://doi.org/10.1111/bju.12363)

[5] [G D Miller, C Moore, V Nair, B Hill, S E Willick, A D Rogol, D Eichner. Hypothalamic-Pituitary-Testicular Axis Effects and Urinary Detection Following Clomiphene Administration in Males. J Clin Endocrinol Metab, 2019;104:906-914.](https://doi.org/10.1210/jc.2018-01159)
