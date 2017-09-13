# tofExampleData

A package to hold just PTR-TOF data files to test and build
vignettes in other packages.


## installation

    library(devtools)
    install_github("bdcaf/rawTof", buildVignettes=T)


## usage

to use the files for reading.

    system.file("extdata", "breath.h5", package = "testdat")
    system.file("extdata", "room_air.h5", package = "testdat")
