---
title: "afcp"
collection: software
order: 1
excerpt: "Estimates the Average Feature Choice Probability (AFCP) in conjoint experiments: how often respondents choose a profile with one feature level when it is directly compared with a profile with another. It also provides diagnostics for when the AFCP diverges from AMCE-style estimands that summarize performance against the full field of alternatives."
language: R
availability: GitHub
coauthors: 'Scott Abramson, Korhan Kocak, and Asya Magazinnik'
links:
  - label: 'github'
    url: 'https://github.com/astrezhnev/afcp'
related:
  - title: 'Aggregation, Interpretation, and Estimation of Preferences in Conjoint Experiments'
    url: '/research/2024-detecting-preference-cycles'
    note: '(working paper)'
---

## Installation

Install the development version from GitHub with `remotes`:

```r
install.packages("remotes")
remotes::install_github("astrezhnev/afcp", build_vignettes = TRUE)
```

The package vignette, `vignette("afcp")`, walks through estimation and the accompanying tests.
