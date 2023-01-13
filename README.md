
<!-- README.md is generated from README.Rmd. Please edit that file -->

# shinysocial

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/shinysocial)](https://CRAN.R-project.org/package=shinysocial)
[![R-CMD-check](https://github.com/r4ds/shinysocial/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/r4ds/shinysocial/actions/workflows/R-CMD-check.yaml)
[![Codecov test
coverage](https://codecov.io/gh/r4ds/shinysocial/branch/main/graph/badge.svg)](https://app.codecov.io/gh/r4ds/shinysocial?branch=main)
<!-- badges: end -->

The goal of shinysocial is to …

## Installation

You can install the development version of shinysocial from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("r4ds/shinysocial")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(shinysocial)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.

## Code of Conduct

Please note that the shinysocial project is released with a [Contributor
Code of
Conduct](https://r4ds.github.io/shinysocial/CODE_OF_CONDUCT.html). By
contributing to this project, you agree to abide by its terms.