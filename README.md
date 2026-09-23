your-repo/
├── README.md
├── requirements.txt
├── data/
├── src/
└── tests/
src/analysis.py
tests/test_analysis.py
 Causal Inference Observational Study

## Task

Estimate the causal effect of an intervention using observational data while accounting for confounding, treatment-selection bias, missing data, and treatment-effect heterogeneity.

## Objective

The goal is to determine whether the observed difference in outcomes between treated and untreated groups can reasonably be attributed to the intervention after adjusting for relevant pre-treatment characteristics.

## Approach

The analysis will:

1. Define the treatment, outcome, and causal estimand.
2. Identify relevant pre-treatment confounders.
3. Examine treatment imbalance and covariate overlap.
4. Estimate the treatment effect using an appropriate causal inference method.
5. Perform balance and robustness diagnostics.
6. Report the estimated effect and uncertainty.

## Verification

The solution will be evaluated using reproducibility, diagnostic checks, numerical agreement with reference results within specified tolerances, and appropriate interpretation of the causal assumptions and limitations
