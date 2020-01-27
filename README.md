
# foofactors3

<!-- badges: start -->
<!-- badges: end -->

The goal of foofactors3 is to combine factors nicely. 

This is an example as part of the "Building tidy tools" workshop at rstudio::conf 2020, on 2020-01-27. 

## Installation

You can install the released version of foofactors3 from GitHub with:

``` r
devtools::install_github("nayefahmad/foofactors3")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(foofactors3)

a <- factor(c("hi", "there"))
b <- factor(c("what's", "up"))
fbind(a, b)

```

## Notes

* Choosing licenses: https://choosealicense.com/ 
