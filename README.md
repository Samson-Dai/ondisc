
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `ondisc`: large-scale computing on single-cell data <img src="man/figures/hex_alt.png" align="right" alt="" width="180" />

<!-- badges: start -->

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/ondisc)](https://cran.r-project.org/package=ondisc)
[![Codecov test
coverage](https://codecov.io/gh/Timothy-Barry/ondisc/branch/main/graph/badge.svg)](https://codecov.io/gh/Timothy-Barry/ondisc?branch=main)
<!-- badges: end -->

Single-cell datasets are growing in size, posing challenges as well as
opportunities to biology researchers. `ondisc` (short for “on-disk
single cell”) is an R package that facilitates computing on large-scale single-cell data. `ondisc` is
especially well-suited to fixed memory and distributed CRISPR screen and
differential expression analyses.

**NOTE**: The package currently is undergoing considerable API changes.
Use with caution. We anticipate that an updated, stable version of the
package (along with detailed documentation) will be available in May 2022.

<!-- Single-cell datasets are growing in size, posing challenges as well as opportunities to biology researchers. `ondisc` (short for "on-disk single cell") is an R package that enables users to easily and efficiently analyze large-scale single-cell data. `ondisc` makes computing on large-scale single-cell data **FUN**:

- **Fast**: `ondisc` is powered by several novel, highly efficient algorithms and data structures. All low-level code is written in C++ or C for maximum performance.
- **Universal**: `ondisc` runs on all platforms, from laptops to supercomputers. `ondisc` works seamlessly when the size of the data exceeds the amount of available memory. 
- **Ntuitive**: `ondisc` leverages ideas from functional programming, making it simple for R users users to pick up and incorporate into their programs.

Take a look at the [tutorials](https://timothy-barry.github.io/ondisc/articles/tutorial_odm_class.html) on the [package website](https://timothy-barry.github.io/ondisc/index.html). -->

## Installation


You can install the development version from Github with:

``` r
install.packages("devtools")
devtools::install_github("timothy-barry/ondisc")
```
