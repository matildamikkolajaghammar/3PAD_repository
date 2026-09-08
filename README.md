# 3PAD repository
### Physiological predictors of postpartum  anxiety and depression (3PAD)
### Matilda Mikkola Jäghammar,MSc, 17/06/26

This repository accompanies the project “Initial and Sustained Pupillary Conflict Responses as Predictors of Antenatal Anxiety and Depression.” It provides the R code used to conduct the analyses presented in the study.

## Overview

The purpose of this repository is to support transparency and reproducibility by documenting the analytical workflow. It includes scripts for data processing, statistical modeling, and generation of results and figures.

The repository is not intended to serve as a standalone reproducible pipeline, as the underlying dataset cannot be shared.

## Data Availability

The raw data used in this project are not included in this repository. Due to the presence of sensitive and confidential participant information, the dataset is not publicly available and cannot be shared.

## Repository Structure

The repository is organized as follows:
markdown/: rmarkdown file containing the full code from beginning to end

models/: Scripts or outputs related to fitted statistical models.

figures/: Code for generating plots and visualizations.

tables/: Code for producing summary tables and model outputs.


## Methods

The analyses were conducted in R and include:

- Table 1 and descriptive statistics

- Multiple imputation for handling missing data (e.g., using the mice package).

- Regression models for count and dichotomous outcomes (e.g., negative binomial, logistic models).



## Reproducibility Notes

Because the raw data are not available, the scripts cannot be executed end-to-end without access to the original dataset. However, the code reflects the exact analytical steps used in the study and is provided to facilitate understanding, review, and reuse of the methods.

Contact

For questions regarding the code or analysis, please contact the repository author.
