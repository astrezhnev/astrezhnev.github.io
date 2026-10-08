---
title: "Omitted variable bias sensitivity analysis with clustered treatment assignment"
collection: research
category: workingpapers
permalink: /research/2026-ovb-sensitivity-clustered
redirect_from:
  - /publication/2026-ovb-sensitivity-clustered
excerpt: "Cinelli and Hazlett (2020) develops a sensitivity analysis method for the linear regression model that parameterizes omitted variable bias in terms of two partial R² parameters capturing the residual variation explained by an omitted confounder in the treatment and outcome respectively. This method is often applied to regressions fit to unit-level data when treatment is assigned at a higher level of aggregation -- as in clustered observational designs. This paper shows that despite the numerical equivalence of the unit-level regression and an appropriately weighted cluster-aggregated regression for estimating the treatment effect, the sensitivity analysis procedure yields different conclusions depending on the chosen level of analysis. The outcome-confounder partial R² reflects both between- and within- group variation but the latter is irrelevant to omitted variable bias as it by construction cannot be explained by a group-level confounder. Straightforward corrections to the robustness value and the extreme scenario analysis from the unit-level regression using Pearson's partial-η recover equivalence between these two approaches. The paper concludes with a point of caution when benchmarking against unit-level covariates and recommends always including cluster-level averages of these covariates as regressors (Mundlak, 1978)."
date: 2026-07-14
paperurl: 'https://arxiv.org/abs/2607.13334'
authors: 'Anton Strezhnev'
links:
  - label: 'paper'
    url: 'https://arxiv.org/abs/2607.13334'
citation: 'Strezhnev, Anton. &quot;Omitted variable bias sensitivity analysis with clustered treatment assignment.&quot; Working Paper.'
---
