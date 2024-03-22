# Causal_Impact_of_Healthcare_Intervention
# Causal Analysis on Health Expenditure and Coverage

## Overview

This study presents a focused causal analysis on the impact of policy interventions on health-related expenditures and coverage. The research utilized advanced econometric models to estimate the effects of policy changes, providing insights into health economics and policy efficacy.

## Introduction

With healthcare at the forefront of public policy, understanding the causal effects of legislative changes on health expenditures and coverage is crucial. This project applies econometric techniques to investigate the relationship between policy intervention and healthcare financial metrics, offering a data-driven basis for policy evaluation and decision-making.

## Data

The analysis used panel data encapsulating various healthcare spending metrics (`spendHosp`, `spendOff`, `spendRx`, `spendTotal`) and coverage rates (`coverageRate`), with a rigorous approach to isolate the causal impact of policy interventions.

## Methodology

### Pre-Post Intervention Analysis

The research design employs a pre-post intervention method, comparing groups before and after the policy implementation to infer causal relationships. The approach includes:

- Identifying and segmenting treatment and control groups based on exposure to the policy.
- Utilizing regression techniques to control for confounding factors and capture the net effect of the intervention.

### Regression Models

Multiple regression models were developed to quantify the effect, adjusting for demographic covariates. The models were used to test the hypothesis that the policy intervention significantly affected healthcare spending and coverage.

## Findings

The study's findings indicated a notable difference in health expenditures and coverage between the pre- and post-intervention phases, supporting the hypothesis of a significant policy impact.

## Repository Contents

- `/Data`: Contains the datasets used in the analysis.
- `/Scripts`: R scripts for data preprocessing, analysis, and modeling.
- `/Results`: Output files including statistical summaries, coefficients, and visualizations.

## Running the Analysis

To reproduce the study's findings:

1. Clone the repository to your local machine.
2. Install the required R packages.
3. Execute the scripts in the `/Scripts` directory, following the sequence outlined in the `main.R` file.
4. Review the results in the `/Results` directory.

## Contributing

We welcome contributions to enhance the analysis, such as alternative modeling approaches, additional covariates, or extended datasets. Please submit pull requests with a clear description of your changes.




