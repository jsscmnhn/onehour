
<!-- README.md is generated from README.Rmd. Please edit that file -->

The goal of roundR is to offer a numeric rounding to the nearest
integer, as opposed to the \[base::round()\] default to round to the
nearest *even* integer.

## INSTALLATION
devtools::install_github("jsscmnhn/onehour")

## EXAMPLE

``` r
library(roundR)
## basic example code
round(2.5)
```

    ## [1] 2

``` r
round_to_integer(2.5)
```

    ## [1] 3
