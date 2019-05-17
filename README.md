# codeForKDD2019
Code for *A permutation approach to assess confounding in machine learning applications for digital health* published in  KDD'19

This project contains the code used to generate the results and figures in the manuscript. Here, is a description:

```
utility_functions_kdd.R:
```
Contains the R functions functions used to simulate the synthetic datasets, 
generate the restricted permutation null distribution, compute AUCs and etc.

```
run_simulations_H1c_H1d.R,
run_simulations_H1c_H0d.R,
run_simulations_H0c_H0d.R,
run_simulations_H0c_H1d.R:
```
Contain the code used to generate the simulation study results.

```
generate_simulation_study_figures.R:
````
Generates Figures 4 and 5.

```
real_data_illustrations.R:
```
Runs the comparison of confounding adjustment methods using the
mPower data. It contains a number of additional utility functions needed to
shape the data and run the analysis. The script also contains the code to 
generate Figures 6, 8, 9, and 10 in the main text, and Figure S2 in the 
Supplement.

```
age_discretization_figure.R:
```

Generates the restricted permutation null distributions for 4 distinct
age discretizations and plot Figure 7.

```
accounting_for_confounder_response_association_in_target_pop.R:
```
Generates the results presented in Section 5.

```
algorithm_3.R:
```
Generates Supplementary Figure S1.
