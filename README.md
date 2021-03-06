[![Build Status](https://travis-ci.org/renozao/doRNG.png?branch=master)](https://travis-ci.org/renozao/doRNG)
[![codecov](https://codecov.io/gh/renozao/doRNG/branch/master/graph/badge.svg)](https://codecov.io/gh/renozao/doRNG)

# Introduction

This `doRNG` package provides functions to perform reproducible parallel foreach loops, 
using independent random streams as generated by L'Ecuyer's combined multiple-recursive generator [L'Ecuyer (1999)].
It enables to easily convert standard %dopar% loops into fully reproducible loops, _independently_ of the number of workers, 
the task scheduling strategy, or the chosen parallel environment and associated foreach backend.

The package `doRNG` is available from CRAN at https://cran.r-project.org/web/packages/doRNG.
The development project is hosted on `GitHub` at https://github.com/renozao/doRNG.
