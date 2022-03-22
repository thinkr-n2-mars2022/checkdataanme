
<!-- README.md is generated from README.Rmd. Please edit that file -->

# checkdataanme

<!-- badges: start -->
<!-- badges: end -->

The goal of checkdataanme is to check the data integrity of the input
dataset

## Installation

You can install the development version of checkdataanme from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("thinkr-n2-mars2022/checkdataanme")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(checkdataanme)
## basic example code
```

``` r
datafile <- system.file("nyc_squirrels_sample.csv", package = "checkdataanme")
nyc_squirrels <- read.csv(datafile)
check_data_integrity(nyc_squirrels)
#> OK
```
