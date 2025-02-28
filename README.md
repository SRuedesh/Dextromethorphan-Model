# Dextromethophan-Model
Physiologically-Based Pharmacokinetic (PBPK) Modeling of Dextromethorphan, its CYP2D6 Drug-Gene Interactions (DGIs) and Interindividual Variability Within Activity Score Groups
## Repository Files 
Within this repository, we distribute a whole-body PBPK model of dextromethorphan and its metabolites dextrorphan and dextrorphan *O*-glucuronide. The model has been carefully developed and evaluated for the prediction of dextromethorphan, dextrorphan and dextrorphan *O*-glucuronide plasma concentrations after intravenous and oral administration over a wide dose range (5 to 80 mg).

The PBPK model was developed to describe the effect of genetic variants in the *CYP2D6* gene on the pharmacokinetics of dextromethorphan. For this purpose, CYP2D6 k<sub>cat</sub> values were optimized for different CYP2D6 activity scores. Additionally, the interindividual variability in CYP2D6 activity score groups was explored by optimizing individual CYP2D6 k<sub>cat</sub> values and subsequently performing a regression analysis.

The model is split in two snapshot files:
- [Aggregated Simulations](./dextromethorphan_aggregated_simulations.json): Contains aggregated profiles used for model building and evaluation.
- [Individual Simulations](./dextromethorphan_individual_simulations.json): Contains individual profiles for 72 individuals used for the analysis of interindividual variability. 

For further details on model development and evaluation as well as extensive documentation of the modeling process, please refer to [[1]](https://onlinelibrary.wiley.com/doi/10.1002/psp4.12776).

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## Reference
[[1] Rüdesheim S, Selzer D, Fuhr U, Schwab M, Lehr T. Physiologically-based pharmacokinetic modeling of dextromethorphan to investigate interindividual variability within CYP2D6 activity score groups. *CPT Pharmacometrics Syst Pharmacol.* 2022;00:1- 18.](https://onlinelibrary.wiley.com/doi/10.1002/psp4.12776)