[![Travis-CI Build Status](https://travis-ci.org/Hackout3/saphy.svg?branch=master)](https://travis-ci.org/Hackout3/saphy)

[![Coverage Status](https://img.shields.io/codecov/c/github/Hackout3/saphy/master.svg)](https://codecov.io/github/Hackout3/saphy?branch=master)

# saphy: sequential analysis of phylogenies

This package contains methods for the sequential (real-time, online) analysis of phylogenies and sequence data.

![Schema v1.0] (inst/scheme.png)

# Installing the package

To install the devel version of the package, type:

```r
devtools::install_github(c("bdearlove/treeImbalance","emvolz-phylodynamics/phydynR","Hackout3/saphy"),build_vignettes=TRUE)
#devtools::install_github("Hackout3/saphy",build_vignettes=TRUE)
```

Note that this requires the package *devtools* installed.

Note if using a mac, you will need lgfortran and lquadmath libraries installed before hand in order to compile rhydynR:
curl -O http://r.research.att.com/libs/gfortran-4.8.2-darwin13.tar.bz2
sudo tar fvxz gfortran-4.8.2-darwin13.tar.bz2 -C /

### Contributors (by alphabetic order):
- Simon Frost (@sdwfrost)
- Don Klinkenberg (@donkeyshot)
- Yu Luo (@yumcgill)
- OJ Watson (@OJWatson)

Maintainer (temporary): Simon Frost (sdwfrost@gmail.com)
