# Software Packages

Useful software packages for applied econometrics, causal inference, and reproducible empirical work.

- [Core Econometrics](#core-econometrics)
- [Panel Data and Fixed Effects](#panel-data-and-fixed-effects)
- [Causal Inference](#causal-inference)
- [Difference-in-Differences](#difference-in-differences)
- [Regression Discontinuity](#regression-discontinuity)
- [Synthetic Control](#synthetic-control)
- [Inference and Standard Errors](#inference-and-standard-errors)
- [Tables and Reporting](#tables-and-reporting)

---

## Core Econometrics

- [statsmodels](https://www.statsmodels.org/stable/) - Python package for statistical modeling and econometrics, including regression, discrete choice, time series, and robust covariance estimators.
- [linearmodels](https://pypi.org/project/linearmodels/) - Python package extending statsmodels with panel data, IV, system regression, and asset pricing models.
- [AER](https://cran.r-project.org/package=AER) - R package accompanying *Applied Econometrics with R*, with datasets and applied econometrics tools.
- [ivreg](https://zeileis.github.io/ivreg/) - R package for instrumental-variables regression diagnostics, inference, and visualization.
- [ivreg2](https://ideas.repec.org/c/boc/bocode/s425401.html) - Stata module for IV/GMM estimation with robust, clustered, and weak-instrument diagnostics.

## Panel Data and Fixed Effects

- [fixest](https://lrberge.github.io/fixest/) - R package for fast OLS, GLM, IV, and fixed-effects estimation with flexible standard errors.
- [PyFixest](https://pyfixest.org/) - Python package mirroring fixest for high-dimensional fixed-effects regressions, IV, GLMs, and event studies.
- [reghdfe](https://github.com/sergiocorreia/reghdfe) - Stata package for linear and IV models with multiple high-dimensional fixed effects.
- [plm](https://cran.r-project.org/package=plm) - R package for linear panel-data models.
- [FixedEffectModels.jl](https://github.com/FixedEffects/FixedEffectModels.jl) - Julia package for fast linear models with high-dimensional fixed effects.

## Causal Inference

- [DoubleML](https://docs.doubleml.org/) - R and Python package for double/debiased machine learning.
- [grf](https://grf-labs.github.io/grf/) - R package for generalized random forests, including causal forests and heterogeneous treatment effects.
- [EconML](https://www.pywhy.org/EconML/) - Python package for machine-learning-based heterogeneous treatment effect estimation.
- [DoWhy](https://www.pywhy.org/dowhy/) - Python package for graph-based causal inference workflows and robustness checks.
- [CausalML](https://github.com/uber/causalml) - Python package for uplift modeling and causal machine learning.
- [Matching](https://cran.r-project.org/package=Matching) - R package for multivariate and propensity-score matching.

## Difference-in-Differences

- [did](https://bcallaway11.github.io/did/) - R package for difference-in-differences with multiple time periods.
- [DRDID](https://psantanna.com/DRDID/) - R package for doubly robust difference-in-differences estimators.
- [didimputation](https://cran.r-project.org/package=didimputation) - R package implementing the Borusyak, Jaravel, and Spiess imputation estimator.
- [did2s](https://cran.r-project.org/package=did2s) - R package for two-stage difference-in-differences estimation.
- [HonestDiD](https://github.com/asheshrambachan/HonestDiD) - R package for sensitivity analysis and robust inference in event-study designs.
- [csdid](https://ideas.repec.org/c/boc/bocode/s458976.html) - Stata implementation of Callaway and Sant'Anna difference-in-differences estimators.
- [eventstudyinteract](https://github.com/lsun20/EventStudyInteract) - Stata package for interaction-weighted event-study estimation.

## Regression Discontinuity

- [rdrobust](https://rdpackages.github.io/rdrobust/) - R, Stata, and Python implementations for robust inference and graphical analysis in regression discontinuity designs.
- [rddensity](https://rdpackages.github.io/rddensity/) - R, Stata, and Python tools for manipulation testing in regression discontinuity designs.
- [rdlocrand](https://rdpackages.github.io/rdlocrand/) - R and Stata tools for local-randomization analysis in regression discontinuity designs.

## Synthetic Control

- [Synth](https://cran.r-project.org/package=Synth) - R package for the synthetic control method for comparative case studies.
- [augsynth](https://github.com/ebenmichael/augsynth) - R package for augmented synthetic control methods.
- [gsynth](https://cran.r-project.org/package=gsynth) - R package for generalized synthetic control and interactive fixed-effects models.
- [scpi](https://nppackages.github.io/scpi/) - R, Stata, and Python package for prediction, estimation, and inference with synthetic controls.
- [synthdid](https://github.com/synth-inference/synthdid) - R package for synthetic difference-in-differences.

## Inference and Standard Errors

- [sandwich](https://sandwich.r-forge.r-project.org/) - R package for model-robust covariance matrix estimators.
- [clubSandwich](https://jepusto.github.io/clubSandwich/) - R package for cluster-robust variance estimators with small-sample corrections.
- [fwildclusterboot](https://s3alfisc.github.io/fwildclusterboot/) - R package for fast wild cluster bootstrap inference.
- [boottest](https://github.com/droodman/boottest) - Stata package for wild bootstrap inference.
- [wildboottestjlr](https://github.com/droodman/WildBootTests.jl) - Julia implementation of wild bootstrap tests.

## Tables and Reporting

- [modelsummary](https://modelsummary.com/) - R package for publication-ready regression tables and data summaries.
- [marginaleffects](https://marginaleffects.com/) - R and Python package for predictions, comparisons, slopes, marginal means, and hypothesis tests.
- [broom](https://broom.tidymodels.org/) - R package for converting model output into tidy data frames.
- [stargazer](https://cran.r-project.org/package=stargazer) - R package for regression and summary-statistics tables.
- [estout](https://github.com/benjann/estout) - Stata package for regression tables and result exports.
