
<!-- README.md is generated from README.Rmd. Please edit that file -->

# finddxtemplate <img src="man/figures/logo.png" align="right" alt="" width="120" />

<!-- badges: start -->

[![R build
status](https://github.com/dsbbfinddx/finddxtemplate/workflows/R-CMD-check/badge.svg)](https://github.com/dsbbfinddx/finddxtemplate/actions)
<!-- [![codecov test coverage](https://app.codecov.io/gh/ThinkR-open/fusen/branch/master/graph/badge.svg?token=V0HOSAY8WW)](https://app.codecov.io/gh/ThinkR-open/fusen) -->
<!-- [![](https://cranlogs.r-pkg.org/badges/fusen)](https://cran.r-project.org/package=fusen) -->
<!-- badges: end -->

The `{finddxtemplate}` package provides design tools to create a Rmd
template for html documents.

Current version is 0.1.0.

The documentation is available here:

-   pkgdown: <https://connect.thinkr.fr/finddxtemplate-pkgdown-website/>
-   coverage report:
    <https://connect.thinkr.fr/finddxtemplate-pkgdown-website/coverage.html>

## HTML template

An overview of the HTML template is available here:
<https://connect.thinkr.fr/finddxtemplate-pkgdown-website/rmd_template.html>

Or in command line:

``` r
browseURL(system.file("rmarkdown", "rmd_template.html", package = "finddxtemplate"))
```

## Installation

You can install the package with:

``` r
if (requireNamespace("remotes")){install.packages("remotes")}
remotes::install_local(path = "path/to/finddxtemplate_0.1.0.tar.gz", 
                       repos = "http://cran.rstudio.com", 
                       type = "source")
```

## Use

-   Open a classical RStudio project File \> New Project…
-   Open a classical R Markdown file File \> New File \> R Markdown…
-   Update the YAML header at the top of the file by:
    -   Adding the `logo` field
    -   Changing the `output` field

``` r
---
title: "My report"
author: "Arthur Bréant"
date: "1/13/2022"
logo: "`r system.file('logo', 'logo.svg', package = 'finddxtemplate')`"
output: finddxtemplate::html_document_find
---
```

-   Knit

## Documentation

Open the pkgdown:

``` r
finddxtemplate::open_pkgdown()
```

Two vignettes are available:

-   *Package installation*
-   *Integration of the FIND graphic design in R Markdown reports*
