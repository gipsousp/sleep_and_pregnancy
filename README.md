
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sqlr.pregnancy <a href='https://gipsousp.github.io/sqlr.pregnancy'><img src='man/figures/logo.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/gipsousp/sqlr.pregnancy/workflows/R-CMD-check/badge.svg)](https://github.com/gipsousp/sqlr.pregnancy/actions)
[![Travis build
status](https://travis-ci.com/gipsousp/sqlr.pregnancy.svg?branch=master)](https://travis-ci.com/gipsousp/sqlr.pregnancy)
[![Codecov test
coverage](https://codecov.io/gh/gipsousp/sqlr.pregnancy/branch/master/graph/badge.svg)](https://codecov.io/gh/gipsousp/sqlr.pregnancy?branch=master)
[![License:
MIT](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)
<!-- badges: end -->

`sqlr.pregnancy` is an R package with the research compendium of the
project: expression of the sleep-wake cycle throughout pregnancy: a
systematic quantitative literature review. The aim of `sqlr.pregnancy`
is to facilitate the research work, in addition to contributing to the
reproducibility of the research.

The assemble of this package was inspired by Ben Marwick, Carl Boettiger
& Lincoln Mullen article [“Packaging Data Analytical Work Reproducibly
Using R (and Friends)”](https://doi.org/10.1080/00031305.2017.1375986).

Learn more about Systematic Quantitative Literature Reviews at
<http://bit.ly/2OMxvcD>.

## Installation

`sqlr.pregnancy` is still at the
[experimental](https://lifecycle.r-lib.org/articles/stages.html#experimental)
stage of development, that means that people can use the package and
provide feedback, but it comes with no promises for long term stability.

You can install `sqlr.pregnancy` from GitHub with:

``` r
# install.packages("sqlr.pregnancy")
devtools::install_github("gipsousp/sqlr.pregnancy", dependencies = TRUE)
```

## Citation

If you use `sqlr.pregnancy` in your research, please consider citing it.
We put a lot of work to build and maintain a free and open-source R
package. You can find the `sqlr.pregnancy` citation below.

``` r
citation("sqlr.pregnancy")
#> 
#> To cite sqlr.pregnancy in publications use:
#> 
#>   Sales, A. R. V., Vartanian, D., Rodrigues, I., Benedito-Silva, A. A.,
#>   Pedrazzoli, M. (2021). sqlr.pregnancy: an R package with the research
#>   compendium of the project: expression of the sleep-wake cycle
#>   throughout pregnancy: a systematic quantitative literature review.
#>   Retrieved from https://gipsousp.github.io/sqlr.pregnancy/.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Unpublished{,
#>     title = {sqlr.pregnancy: an R package with the research compendium of the project: expression of the sleep-wake cycle throughout pregnancy: a systematic quantitative literature review},
#>     author = {Alicia Rafaelly Vilefort Sales and Daniel Vartanian and Isadora Rodrigues and Ana Amelia Benedito-Silva and Mario Pedrazzoli},
#>     year = {2021},
#>     url = {https://gipsousp.github.io/sqlr.pregnancy/},
#>     note = {Lifecycle: experimental},
#>   }
```
