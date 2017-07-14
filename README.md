
[![minimal R version](https://img.shields.io/badge/R%3E%3D-3.3.3-6666ff.svg)](https://cran.r-project.org/) [![GitHub (pre-)release](https://img.shields.io/github/release/timtrice/rrricanesdata/all.svg)](https://github.com/timtrice/rrricanesdata/tags) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/rrricanesdata)](https://cran.r-project.org/package=rrricanesdata) [![Build Status](https://img.shields.io/travis/timtrice/rrricanesdata/master.svg)](https://travis-ci.org/timtrice/rrricanesdata) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/timtrice/rrricanesdata/master.svg)](https://ci.appveyor.com/project/timtrice/rrricanesdata)

rrricanesdata
=============

`rrricanesdata` is the complimentary dataset for `[rrricanes](https://github.com/timtrice/rrricanes)`. Currently it contains all product datasets for every cyclone that has developed in the north Atlantic and northeast Pacific basins since 1998.

`rrricanesdata` will be updated on the first of every month.

Datasets
--------

### `adv`

     * Key: Unique identifier of cyclone
     * Adv: Advisory number
     * Date: Date and time of advisory
     * Status: Classification of cyclone
     * Name: Name of cyclone
     * Lat: Latitude of cyclone center
     * Lon: Longitude of cyclone center
     * Wind: Maximum sustained one-minute winds in knots
     * Gust: Maximum sustained one-minute gusts in knots
     * Pressure: Minimum central pressure in millibars
     * PosAcc: Position accuracy of cyclone in nautical miles
     * FwdDir: Compass angle of forward motion
     * FwdSpeed: Forward speed in miles per hour
     * Eye: Size of eye in nautical miles
     * SeasNE: Radius of 12ft seas in northeast quadrant
     * SeasSE: Radius of 12ft seas in southeast quadrant
     * SeasSW: Radius of 12ft seas in southwest quadrant
     * SeasNW: Radius of 12ft seas in northwest quadrant

### `discus`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Adv: Advisory Number
    * Date: Date of advisory issuance
    * Key: ID of cyclone
    * Contents: Text content of product

### `fcst`

     * Key: Unique identifier of cyclone
     * Adv: Advisory number
     * Date: Date and time of advisory
     * FcstDate: Forecast date and time in UTC
     * Lat: Forecast latitude
     * Lon: Forecast Longitude
     * Wind: Forecast wind in knots
     * Gust: Forecast gust in knots

### `fcst_wr`

     * Key: Unique identifier of cyclone
     * Adv: Advisory number
     * Date: Date and time of advisory
     * FcstDate: Forecast date and time in UTC
     * WindField: Minimum sustained wind field for quadrants
     * NE: Radius in nautical miles for northeast quadrant
     * SE: Radius in nautical miles for southeast quadrant
     * SW: Radius in nautical miles for southwest quadrant
     * NW: Radius in nautical miles for northwest quadrant

### `fstadv`

     * Status: Classification of cyclone
     * Name: Name of cyclone
     * Adv: Advisory number
     * Date: Date and time of advisory
     * Key: Unique identifier of cyclone
     * Lat: Latitude of cyclone center
     * Lon: Longitude of cyclone center
     * Wind: Maximum sustained one-minute winds in knots
     * Gust: Maximum sustained one-minute gusts in knots
     * Pressure: Minimum central pressure in millibars
     * PosAcc: Position accuracy of cyclone in nautical miles
     * FwdDir: Compass angle of forward motion
     * FwdSpeed: Forward speed in miles per hour
     * Eye: Size of eye in nautical miles
     * NE64: Radius of >=64kt winds in northeast quadrant
     * SE64: Radius of >=64kt winds in southeast quadrant
     * SW64: Radius of >=64kt winds in southwest quadrant
     * NW64: Radius of >=64kt winds in northwest quadrant
     * NE50: Radius of >=50kt winds in northeast quadrant
     * SE50: Radius of >=50kt winds in southeast quadrant
     * SW50: Radius of >=50kt winds in southwest quadrant
     * NW50: Radius of >=50kt winds in northwest quadrant
     * NE34: Radius of >=34kt winds in northwest quadrant
     * SE34: Radius of >=34kt winds in southeast quadrant
     * SW34: Radius of >=34kt winds in southwest quadrant
     * NW34: Radius of >=34kt winds in northwest quadrant
     * Hr\{n\}FcstDate: Forecast valid date
     * Hr\{n\}Lat: Forecast latitude in `n` hours
     * Hr\{n\}Lon: Forecast longitude in `n` hours
     * Hr\{n\}Wind: Forecast maximum wind in `n` hours
     * Hr\{n\}Gust: Forecast maximum gust in `n` hours
     * Hr\{n\}NE64: Forecast wind radius in `n` hours
     * Hr\{n\}SE64: Forecast wind radius in `n` hours
     * Hr\{n\}SW64: Forecast wind radius in `n` hours
     * Hr\{n\}NW64: Forecast wind radius in `n` hours
     * Hr\{n\}NE50: Forecast wind radius in `n` hours
     * Hr\{n\}SE50: Forecast wind radius in `n` hours
     * Hr\{n\}SW50: Forecast wind radius in `n` hours
     * Hr\{n\}NW50: Forecast wind radius in `n` hours
     * Hr\{n\}NE34: Forecast wind radius in `n` hours
     * Hr\{n\}SE34: Forecast wind radius in `n` hours
     * Hr\{n\}SW34: Forecast wind radius in `n` hours
     * Hr\{n\}NW34: Forecast wind radius in `n` hours
     * SeasNE: Radius of 12ft seas in northeast quadrant
     * SeasSE: Radius of 12ft seas in southeast quadrant
     * SeasSW: Radius of 12ft seas in southwest quadrant
     * SeasNW: Radius of 12ft seas in northwest quadrant

### `posest`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Date: Date of advisory issuance
    * Contents: Text content of product

### `prblty`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Adv: Advisory Number
    * Date: Date of advisory issuance
    * Location: Location for which the probability statistics rely
    * A: Probability of a strike within the next 12 hours
    * B: Probability of a strike between 12 and 24 hours
    * C: Probability of a strike between 24 and 36 hours
    * D: Probability of a strike between 36 and 48 hours
    * E: Probability of a strike between 48 and 72 hours

### `public`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Adv: Advisory Number
    * Date: Date of advisory issuance
    * Key: Unique ID of the cyclone
    * Contents: Text content of product

### `storms`

    * Key: Storm ID
    * Name: Storm name
    * Wind: Peak wind speed in knots
    * StartDate: Date/time of first advisory
    * EndDate: Date/time of last advisory

### `update`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Date: Date of advisory issuance
    * Key: Unique ID of cyclone
    * Contents: Text content of product

### `wndprb`

    * Status: Classification of storm, e.g., Tropical Storm, Hurricane,
    etc.
    * Name: Name of storm
    * Adv: Advisory Number
    * Date: Date of advisory issuance
    * Wind: Minimum wind speed for which probabilities reference
    * Wind12: Probability of sustained `Wind` within 12 hours
    * Wind24: Probability of sustained `Wind` within 24 hours
    * Wind24Cum: Cumulative probability through 24 hours
    * Wind36: Probability of sustained `Wind` within 36 hours
    * Wind36Cum: Cumulative probability through 36 hours
    * Wind48: Probability of sustained `Wind` within 48 hours
    * Wind48Cum: Cumulative probability through 48 hours
    * Wind72: Probability of sustained `Wind` within 72 hours
    * Wind72Cum: Cumulative probability through 72 hours
    * Wind96: Probability of sustained `Wind` within 96 hours
    * Wind96Cum: Cumulative probability through 96 hours
    * Wind120: Probability of sustained `Wind` within 120 hours
    * Wind120Cum: Cumulative probability through 120 hours

### `wr`

     * Key: Unique identifier of cyclone
     * Adv: Advisory number
     * Date: Date and time of advisory
     * Windfield: Minimum wind speed expected
     * NE: Radius of `Windfield` in the northeast quadrant
     * SE: Radius of `Windfield` in the southeast quadrant
     * SW: Radius of `Windfield` in the southwest quadrant
     * NW: Radius of `Windfield` in the northwest quadrant

Getting Started
---------------

Please view the vignette 'Getting Started':

``` r
vignette("getting_started", package = "rrricanesdata")
```

[Online documentation](https://timtrice.github.io/rrricanesdata/) is also available.

### Prerequisites

`rrricanesdata` requires an active internet connection as data is extracted from online sources.

Linux users must also have the `libgdal-dev`, `libproj-dev` and `libxml2-dev` packages installed.

To use high resolution tracking maps you will need to install the `rnaturalearthhires` package.

``` r
install.packages("rnaturalearthhires",
                 repos = "http://packages.ropensci.org",
                 type = "source")
```

### Installing

`rrricanesdata` is currently only available in GitHub. It can be installed using the `devtools` package:

``` r
devtools::install_github("timtrice/rrricanesdata", build_vignettes = TRUE)
```

Built With
----------

-   [R 3.3.3](https://www.r-project.org/) - The R Project for Statistical Computing

Contributing
------------

Please read [CONTRIBUTING.md](https://github.com/timtrice/rrricanesdata/blob/master/.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
----------

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/timtrice/Hurricanes/tags).

Authors
-------

-   **Tim Trice** - *Initial work* - [timtrice](https://github.com/timtrice)

See also the list of [contributors](https://github.com/timtrice/rrricanesdata/contributors) who participated in this project.

License
-------

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Acknowledgments
---------------

-   NA

Known Data Quality Issues
-------------------------

1.  Hurricane Juan (AL152003), Adv 15; no status leads to improper `Status` and `Name` values in some datasets. ([\#82](https://github.com/timtrice/rrricanesdata/issues/82))
