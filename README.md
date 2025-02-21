
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pets

The goal of pets is to provide a simple means for people to express
their feelings about pets. At present, the package only contains one
function: `cats()`.

<!-- badges: start -->
<!-- badges: end -->

The goal of pets is to …

## Installation

You can install the development version of pets from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("SandyHoey/pets")
```

## Example

Here are two simple examples that allow you to express your feelings
about cats.

``` r
library(pets)

## if you like cats
cats(TRUE)
#> [1] "I love cats!"

## if you don't like cats
cats(FALSE)
#> [1] "I am not a cat person."
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
