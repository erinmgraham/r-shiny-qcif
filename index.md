---
site: sandpaper::sandpaper_site
---

[R Shiny] is a popular R package that allows you to transform complex analytics into powerful, user-friendly interactive visualisation tools. 

This lesson is designed to provide an introduction to [R Shiny] and demonstrate how you can use it to create web apps and more interactive data visualisations. It is derived from the Carpentries Incubator [R Shiny Geospatial] lesson and rewritten for QCIF delivery.

::::::::::::::::::::::::::::::::::::::::::  prereq

## Prerequisites

Carpentry's teaching is hands-on, so participants are encouraged to use their own computers to ensure the proper setup of tools for an efficient workflow. To most effectively use these materials, please make sure to download the data and install everything before working through this lesson.

### R Skill Level

This lesson assumes you have prior knowledge of `R` and experience with `RStudio`. If you've never
used `R` or `RStudio` before, or need a refresher, start with 
[R for Reproducible Scientific Analysis].

### Install Software and Download Data

This lesson assumes you have `R` and `RStudio` installed on your computer.

- Download and install the [latest version of R].
- Download and install [RStudio].
- Install R Packages:
  - [shinyr]
  - [shinythemes]
  - [tidyverse]

### Download Data

The [csv file used in this lesson](data/bcc_occupation_count_2041.csv) lesson was generated from data from an [Employment Projection Model]: A set of employment forecasts which reflect the Brisbane City Council view of the likely SEQ Regional Employment patterns in the period between 2011 and 2041. They were prepared by the National Institute of Economic and Industrial Research.

::::::::::::::::::::::::::::::::::::::::::::::::::

[R Shiny]: https://shiny.posit.co/
[R Shiny Geospatial]: https://cobalt-casco.github.io/r-shiny-geospatial/
[R for Reproducible Scientific Analysis]: https://swcarpentry.github.io/r-novice-gapminder/
[latest version of R]: https://cran.r-project.org/
[RStudio]: https://posit.co/downloads/
[Employment Projection Model]: https://data.brisbane.qld.gov.au/explore/dataset/occupation-employment-by-usual-resident-employment/information/