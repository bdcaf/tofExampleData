# tofExampleData

** This is an outdated package. ** Its purpose always only was to provide data for the `rawTof` and `tofTools` vignettes and tests. Do no longer use this package.


A package to hold just PTR-TOF data files to test and build
vignettes in other packages.

The measurements were taken by me on 2017-09-11.  Both measurments are 60 seconds long with sampling rate of 1 second.  
`room_air.h5` is a measurement of room air in the lab.  `breath.h5` a measurement of breath by exhaling at rest through a straw.  The breathing cycles can be observed in masses 59 and 69, which show aroung 4 second duration for each breath stroke.


## installation

    library(devtools)
    install_github("bdcaf/rawTof", buildVignettes=T)


## usage

to use the files for reading.

    system.file("extdata", "breath.h5", package = "tofExampleData")
    system.file("extdata", "room_air.h5", package = "tofExampleData")
