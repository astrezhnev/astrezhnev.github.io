---
title: "Benchmarking parallel trends violations in regression imputation difference-in-differences"
collection: publications
category: workingpapers
permalink: /publication/2025-benchmarking-parallel-trends
excerpt: 'Difference-in-differences (DiD) studies increasingly use regression imputation methods as an alternative to the conventional two-way fixed effects (TWFE) estimator, fitting a TWFE regression on the controls to impute treated counterfactuals. A common method for obtaining pre-trend placebo estimates uses the same model to impute outcomes for control units -- the default in the popular fect R package. We decompose this "in-sample imputation" estimator into its component 2 x 2 differences-in-differences to show two biases: an attenuation bias driven by redundant differences-in-differences that are zero by construction and a contamination bias resulting from the use of "early adopters" as controls under staggered adoption. These distort both the magnitude and the apparent shape of the pre-treatment trends. We show that both biases are addressed by a simple correction computed from the in-sample imputations. To illustrate, we re-analyze a study of the political effects of the 2008 "shale shock" on Republican vote share in U.S. coal counties (Gazmararian, 2025). While the original analysis used in-sample imputation and concluded pre-trends were small, corrected placebo estimates of pre-trends are comparable in magnitude to the estimated treatment effects. The observed post-2008 Republican gains in coal counties are likely artifacts of longer-running regional trends.'
date: 2025-01-01
paperurl: 'https://osf.io/preprints/socarxiv/ngr3d'
citation: 'Li, Zikai, and Anton Strezhnev. &quot;Benchmarking parallel trends violations in regression imputation difference-in-differences.&quot; Working Paper.'
---

[Download paper here](https://osf.io/preprints/socarxiv/ngr3d)
