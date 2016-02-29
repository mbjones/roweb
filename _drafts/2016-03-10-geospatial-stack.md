---
name: ropensci-geospatial-stack
layout: post
title: Overview of the rOpenSci geospatial stack
date: 2016-03-10
authors:
  - name: Scott Chamberlain
tags:
- R
- API
- geo
- spatial
---



Geospatial data input/output, manipulation, and vizualization are tasks that are common to many disciplines. Thus, we're keenly interested in making great tools in this space. We have an increasing set of spatial tools, which we'll cover lightly, and point to deeper dives on each if any peak your interest.

## geojsonio

<a href="https://cran.rstudio.com/web/packages/geojsonio/"><span class="label label-warning">cran</span></a> <a href="https://github.com/ropensci/geojsonio"><span class="label label-info">github</span></a>

[geojsonio](https://github.com/ropensci/geojsonio) - A tool for converting to and from geojson data. For example:


```r
library("geojsonio")
'xxx'
#> [1] "xxx"
```
## wellknown

<a href="https://cran.rstudio.com/web/packages/wellknown/"><span class="label label-warning">cran</span></a> <a href="https://github.com/ropensci/wellknown"><span class="label label-info">github</span></a>

[wellknown](https://github.com/ropensci/wellknown) - A tool for converting to and from well-known text data. For example:


```r
library("wellknown")
'xxx'
#> [1] "xxx"
```

## gistr

<a href="https://cran.rstudio.com/web/packages/gistr/"><span class="label label-warning">cran</span></a> <a href="https://github.com/ropensci/gistr"><span class="label label-info">github</span></a>

[gistr](https://github.com/ropensci/gistr) - This is not a geospatial tool per se, but it's extremely useful for sharing maps. For example, with just a few lines, you can share an interactive map to GitHub.


```r
library("gistr")
'xxx'
#> [1] "xxx"
```

## lawn

<a href="https://cran.rstudio.com/web/packages/lawn/"><span class="label label-warning">cran</span></a> <a href="https://github.com/ropensci/lawn"><span class="label label-info">github</span></a>

An R client for [turf.js](http://turfjs.org/).


```r
library("lawn")
'xxx'
#> [1] "xxx"
```

## proj

<span class="label label-warning">cran</span> <a href="https://github.com/ropensci/proj"><span class="label label-info">github</span></a>

An R client for [proj4js](https://github.com/proj4js/proj4js), a Javascript library for projections.


```r
library("proj")
'xxx'
#> [1] "xxx"
```

## getlandsat

<span class="label label-warning">cran</span> <a href="https://github.com/ropenscilabs/getlandsat"><span class="label label-info">github</span></a>

An R client to fetch Landsat data


```r
library("getlandsat")
'xxx'
#> [1] "xxx"
```

## siftgeojson

<span class="label label-warning">cran</span> <a href="https://github.com/ropenscilabs/siftgeojson"><span class="label label-info">github</span></a>

Slice and dice GeoJSON just as easily as you would a data.frame.


```r
library("getlandsat")
'xxx'
#> [1] "xxx"
```

## Maps

There's an increasing number of options for mapping in R. rOpenSci has two offerings in this space: `plotly` and `cartographer`.

### plotly

<a href="https://cran.rstudio.com/web/packages/plotly/"><span class="label label-warning">cran</span></a> <a href="https://github.com/ropensci/plotly"><span class="label label-info">github</span></a>

[plotly](https://github.com/ropensci/plotly) is an R client for [Plotly](https://plot.ly/) - a web interface and API for creating interactive graphics.


```r
library("plotly")
'xxx'
#> [1] "xxx"
```

### cartographer

<span class="label label-inverse">cran</span> <a href="https://github.com/ropensci/cartographer"><span class="label label-info">github</span></a>

[cartographer](https://github.com/ropensci/cartographer) - xxdasfaff. Note that `cartographer` is sort of a suspended state of animation. Do checkout the [leaflet pacakge](https://cran.rstudio.com/web/packages/leaflet/) for a more complete solution. For example:


```r
library("cartographer")
'xxx'
#> [1] "xxx"
```

## Maptools Task View

<a href="https://github.com/ropensci/maptools"><span class="label label-info">github</span></a>

[Jeff Hollister](http://jwhollister.com/) is leading the [maptools task view](https://github.com/ropensci/maptools) to organize R mapping tools packages, sources of data, projections, static and interactive mapping, data transformation, and more.