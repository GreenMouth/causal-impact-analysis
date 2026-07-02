# Causal Impact Analysis

Causal inference on time-series interventions using Bayesian Structural Time Series (BSTS) models.

## Overview

This project estimates the causal effect of an intervention on a time series using Bayesian Structural Time Series (BSTS) modeling. By constructing a counterfactual "what would have happened" baseline, it quantifies the incremental impact of an event — for example, a marketing campaign or product change — on an observed metric.

## Contents

| Item | Description |
|------|-------------|
| `CausalImpact.R` | R script running the BSTS-based causal impact analysis. |
| `Model_Output.png` | Plot of the observed series, counterfactual prediction, and estimated effect. |
| `Model_Summary.docx` | Written summary of the model results and interpretation. |

## Requirements

- R
- The `CausalImpact` R package (built on `bsts`)

Install the package in R with:

```r
install.packages("CausalImpact")
```

## Usage

Run the analysis in R:

```r
source("CausalImpact.R")
```

## License

No license has been specified for this repository. Please contact the author before reuse.
