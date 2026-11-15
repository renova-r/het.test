# het.test

White's test for heteroskedasticity of the residuals of vector autoregressive (VAR) models fitted with the vars package, as outlined in Doornik (1996).

Compatibility updates by Renova.

Version 0.1.9001 declares its `methods`, `stats` and `vars` imports in `NAMESPACE` so the namespace loads with its stated dependencies, compares only the first class in the input checks of `whites.htest()`, corrects the package alias in the help page, and adds an `Authors@R` entry while removing the stale `Date` from `DESCRIPTION`. The test statistic computation was not changed.

## Install

Install this release from its GitHub tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/het.test@renova-0.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

het.test is by Sebastian Andersson (maintainer); the original CRAN package is at <https://CRAN.R-project.org/package=het.test>. License: GPL (>= 2); see [COPYING](COPYING).
