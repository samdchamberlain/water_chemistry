<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Travis-CI Build Status](https://travis-ci.org/samdchamberlain/salinity_study.svg?branch=master)](https://travis-ci.org/samdchamberlain/salinity_study)

Salinity study
==============

This package was used the generate the manuscript "Effect of drought-induced salinization on wetland methane emissions, gross ecosystem photosynthesis, and their interactions." by Samuel D. Chamberlain et. al. The /data folder contains half-hourly eddy covariance files used in the analysis, the /R folder contains scripts used to process data and information theory functions, and the /vignettes folder contains the Markdown and bibiography files used to generate the manuscript.

Installation
------------

You can install salinity from github with:

``` r
# install.packages("devtools")
devtools::install_github("samdchamberlain/salinity_study")
```

How to Run
----------

Load package into RStudio and open the 'manuscript.Rmd' within the /vignettes folder. Using RStudio, click the 'Knit' button at the top of the console and this manuscript, and analyses herein, will be re-created.
