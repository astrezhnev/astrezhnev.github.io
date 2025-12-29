---
title: "Benchmarking parallel trends violations in regression imputation difference-in-differences"
collection: publications
category: workingpapers
permalink: /publication/2025-benchmarking-parallel-trends
excerpt: 'Difference-in-differences studies increasingly use regression imputation methods as an alternative to the conventional two-way fixed effects (TWFE) model. These approaches fit a single TWFE regression to only control units and use it to impute counterfactuals for treated units, resulting in estimates robust to treatment effect heterogeneity. When evaluating the parallel trends assumption, researchers commonly impute counterfactuals for the same control units that were used in estimating the model---the default "in-sample" option for pre-trends tests in the popular R package fect. We show this approach creates complications for benchmarking the magnitude of potential parallel trends violations by severely understating actual pre-trends, making them appear small when they are actually substantial. A simple correction, also implemented in fect, excludes the period being tested when fitting the model ("leave-one-out"), eliminating this attenuation bias. We demonstrate the practical importance of this correction through re-analysis of a recent study on the political effects of the "shale shock" (Gazmararian, 2025). While the original analysis used in-sample imputation and concluded pre-trends were negligible, our corrected approach reveals pre-trends comparable in magnitude to the estimated treatment effects. The observed positive effects of the 2008 fracking boom on Republican presidential vote share in U.S. coal counties are likely artifacts of longer-running trends in these regions.'
date: 2025-01-01
paperurl: 'https://osf.io/preprints/socarxiv/ngr3d'
citation: 'Li, Zikai, and Anton Strezhnev. &quot;Benchmarking parallel trends violations in regression imputation difference-in-differences.&quot; Working Paper.'
---

[Download paper here](https://osf.io/preprints/socarxiv/ngr3d)
