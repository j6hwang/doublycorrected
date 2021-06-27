# doublycorrected
STATA code for Doubly Corrected Robust Variance Estimator for Linear GMM as in Hwang, Kang, and Lee (2019, Working Paper), Hansen and Lee (2019, Working Paper)

This implements robust-standard error of one-step (2SLS), two-step, and iterated-GMM and provides finite sample corrections in addition to the well-known Windmeijer (2005, Journal of Econometrics) and conventional (heteroskedasticity-robust) standard error. Further, reported standard error is also valid under general model misspecification (e.g., invalid instruments, misspecified lag specifications, heterogeneous effects, etc).

dcivreg.ado : Stata code for implementing doubly-corrected robust variance estimator in cross-sectional IV/GMM setup. See attached help file (dcivreg.sthlp) for more details.

dcxtab.ado : Stata code for implementing doubly-corrected robust variance estimator in dynamic panel data setup. Usage of command is similar to xtabond2.

Contributors:

Jungbin Hwang (https://hwang.econ.uconn.edu/), University of Connecticut

Byunghoon Kang (https://sites.google.com/site/davidbhkang/), Lancaster University

Seojeong Lee (https://sites.google.com/site/misspecifiedjay/), University of New SouthWales

Related Papers:

Hansen, B. E., & Lee, S. (2021). Inference for iterated GMM under misspecification. Econometrica, 89(3), 1419-1447.

Hwang, J., Kang, B., & Lee, S. (2021). A doubly corrected robust variance estimator for linear GMM. Journal of Econometrics.
