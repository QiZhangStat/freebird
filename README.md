
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Build
Status](https://travis-ci.org/rzhou14/freebird.svg)](https://travis-ci.org/rzhou14/freebird)
[![Package-License](http://img.shields.io/badge/license-GPL%20\(%3E=2\)-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-2.0.html)

[![Coverage
status](https://codecov.io/gh/rzhou14/freebird/branch/master/graph/badge.svg)](https://codecov.io/github/rzhou14/freebird?branch=master)

<!--
[![CRAN Version Badge](http://www.r-pkg.org/badges/version/freebird)](https://cran.r-project.org/package=freebird)
[![CRAN Status](https://cranchecks.info/badges/worst/freebird)](https://cran.r-project.org/web/checks/check_results_freebird.html)
[![RStudio CRAN Mirror's Monthly Downloads](http://cranlogs.r-pkg.org/badges/freebird?color=brightgreen)](http://www.r-pkg.org/pkg/freebird)
[![RStudio CRAN Mirror's Total Downloads](http://cranlogs.r-pkg.org/badges/grand-total/freebird?color=brightgreen)](http://www.r-pkg.org/pkg/freebird)

-->

# freebird

The goal of `freebird` is to do estimation and perform inference for
High Dimensional Mediation Analysis.


## Installation

If you have a compiler installed on your computer, then you can install
the development version of freebird from GitHub by using:

``` r
if(requireNamespace("devtools")) install.packages("devtools")
#devtools::install_github("rzhou14/freebird")
devtools::install_github("QiZhangStat/freebird")# The only difference in this folk as on 04/28/2023 was that this folk exports all functions instead of only the main function hilma.
```

We soon hope to have it ready for [CRAN](https://CRAN.R-project.org).

<!--- with:

``` r
install.packages("freebird")
```

-->

## Usage

To use `freebird`, please load the package with:

``` r
library("freebird")
```

## Authors

Ruixuan Zhou and Dave Zhao

Special Thanks to James Balamuta for giving up his lunch hour\!

## License

GPL (\>= 2)
