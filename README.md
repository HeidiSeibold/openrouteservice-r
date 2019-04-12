[![Travis-CI Build
Status](https://travis-ci.org/GIScience/openrouteservice-r.svg?branch=master)](https://travis-ci.org/GIScience/openrouteservice-r)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/GIScience/openrouteservice-r?branch=master&svg=true)](https://ci.appveyor.com/project/aoles/openrouteservice-r)
[![Coverage
Status](https://img.shields.io/codecov/c/github/GIScience/openrouteservice-r/master.svg)](https://codecov.io/github/GIScience/openrouteservice-r?branch=master)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

openrouteservice R client
=========================

*openrouteservice* R package provides easy access to the
[openrouteservice](https://openrouteservice.org) (ORS) API from R. It
allows you to painlessly consume the following services:

-   [directions](https://openrouteservice.org/dev/#/api-docs/directions)
    (routing)
-   [geocode](https://openrouteservice.org/dev/#/api-docs/geocode)
    powered by [Pelias](https://pelias.io)
-   [isochrones](https://openrouteservice.org/dev/#/api-docs/isochrones)
    (accessibilty)
-   time-distance
    [matrix](https://openrouteservice.org/dev/#/api-docs/matrix)
-   [pois](https://openrouteservice.org/dev/#/api-docs/pois) (points of
    interest)
-   [elevation](https://openrouteservice.org/dev/#/api-docs/elevation)
    (SRTM elevation for point and lines geometries)

Disclaimer
----------

By using this package, you agree to the ORS [terms and
conditions](https://openrouteservice.org/terms-of-service/).

Installation
------------

The package is not yet available from CRAN, but you can install the
development version directly from GitHub.

    # install.packages("remotes")
    remotes::install_github("GIScience/openrouteservice-r")

Get started
-----------

See the package
[vignette](https://giscience.github.io/openrouteservice-r/articles/openrouteservice.html)
for an overview of the offered functionality.

Package News
------------

### Changes in version 0.2.0

#### NEW FEATURES

-   Update to openrouteservice API v2
-   Another feat

#### BUG FIXES

-   Some bug

### Changes in version 0.1.25

#### NEW FEATURES

-   Add `ors_elevation` endpoint
-   Another feat
