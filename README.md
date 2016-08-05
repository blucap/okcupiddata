
<!-- README.md is generated from README.Rmd. Please edit that file -->
okcupiddata
===========

[![Build Status](https://travis-ci.org/rudeboybert/okcupiddata.png?branch=master)](https://travis-ci.org/rudeboybert/okcupiddata) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/okcupiddata)](http://cran.r-project.org/package=okcupiddata) [![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/okcupiddata)](http://www.r-pkg.org/pkg/okcupiddata)

R package of OkCupid profile data from Albert Y. Kim, Adriana Escobedo-Land (2015). [OkCupid Profile Data for Introductory Statistics and Data Science Courses](http://www.amstat.org/publications/jse/v23n2/kim.pdf). Journal of Statistics Education, 23(2).

Note:

-   Due to size restrictions, all essay responses are omitted from the package. The complete data can be obtained [here](https://github.com/rudeboybert/JSE_OkCupid).
-   Permission to use this data set was explicitly granted by OkCupid.
-   Usernames are not included.

Installation
------------

COMING SOON: Get the released version from CRAN:

``` r
install.packages("okcupiddata")
```

Or the development version from GitHub:

``` r
# If you haven't installed devtools yet, do so:
# install.packages("devtools")
devtools::install_github("rudeboybert/okcupiddata")
```

Data Sets
---------

To see a list of all data sets, type:

``` r
data(package = "okcupiddata")
```

To load a particular data set, `profiles` for example, type:

``` r
# Cleaned profile data
data(profiles)
# Raw profile data
data(profiles_raw)
```
