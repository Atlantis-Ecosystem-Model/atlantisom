# atlantisom
<!-- badges: start -->
[![R-CMD-check](https://github.com/Atlantis-Ecosystem-Model/atlantisom/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/Atlantis-Ecosystem-Model/atlantisom/actions/workflows/R-CMD-check.yaml)
[![gh-pages](https://github.com/Atlantis-Ecosystem-Model/atlantisom/actions/workflows/pkgdown.yaml/badge.svg)](https://github.com/Atlantis-Ecosystem-Model/atlantisom/actions/workflows/pkgdown.yaml)
<!-- badges: end -->


[Atlantis][Atlantis] operating model. 
Generates data sets from [Atlantis][Atlantis] scenarios.

## Installing the atlantisom R package

You must install from github, using: 

```R
pak::pak("Atlantis-Ecosystem-Model/atlantisom")
```

atlantisom functions are divided into four types:

1. `load` functions that read in output from Atlantis.

2. `create` functions that conduct run multiple `sample` functions to create
   either fishery-independent or fishery-dependent data.

3. `sample` functions for manipulate Atlantis data which signifies the truth.
   These manipulations generate sampled data for use in various estimation models.

4. `write` functions for writing output the disk.

[Atlantis]: http://atlantis.cmar.csiro.au/
