
<!-- README.md is generated from README.Rmd. Please edit that file -->

# finddxtemplate <img src="man/figures/logo.png" align="right" alt="" width="120" />

[![R build
status](https://forge.thinkr.fr/thinkr/missions/finddx/finddxtemplate/badges/main/pipeline.svg)](https://forge.thinkr.fr/finddx/finddxtemplate/-/pipelines)
[![Codecov test
coverage](https://forge.thinkr.fr/thinkr/missions/finddx/finddxtemplate/badges/main/coverage.svg)](https://connect.thinkr.fr/finddxtemplate-pkgdown-website/coverage.html)

The `{finddxtemplate}` package provides design tools to create a Rmd
template for html documents.

Current version is
0.1.0.

<img src="vignettes/figures/html_template.png" width="500" style="display: block; margin: auto;" />

The documentation is available here:

  - pkgdown: <https://connect.thinkr.fr/finddxtemplate-pkgdown-website/>
  - coverage report:
    <https://connect.thinkr.fr/finddxtemplate-pkgdown-website/coverage.html>

## HTML template

An overview of the HTML template is available here:
<https://connect.thinkr.fr/finddxtemplate-pkgdown-website/rmd_template.html>

Or in command
line:

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

Open the pkgdown:

``` r
finddxtemplate::open_pkgdown()
```

Two vignettes are available:

  - *Package installation*
  - *Integration of the FIND graphic design in R Markdown reports*
