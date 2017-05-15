
<!-- README.md is generated from README.Rmd. Please edit that file -->
externalrdata
-------------

[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip) [![Travis-CI Build Status](https://travis-ci.org/jsta/externalrdata.svg?branch=master)](https://travis-ci.org/jsta/externalrdata) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/externalrdata)](https://cran.r-project.org/package=externalrdata) [![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/externalrdata)](https://cran.r-project.org/package=externalrdata)

This package is a template to fetch, cache, and serve data from external sources.

Installation
------------

``` r
# install devtools if not found
# install.packages(devtools)
devtools::install_github("jsta/externalrdata")
```

Usage
-----

``` r
library(externalrdata)
```

### Download external data and store in file system

``` r
temp_get()
```

### Load data

``` r
head(temp_load())
```
