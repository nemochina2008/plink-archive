# plink

This R package was removed from CRAN on 2014-09-20 and moved to the [archives](http://cran.r-project.org/web/packages/plink/index.html). However, others still may find it useful, therefore I this is simply a host of the last archived version which can be installed easily with the `devtools` package. All files are identical to the archived version, excluding the `README.md` file. 

## Installation

To install, type the following into the R console after installing the `devtools` package:

```r
library(devtools)
install_github('philchalmers/plink-archived')

# load the package
library(plink)
```

Prior to it's removal, the `mirt` package also supported a conversion function to port parameters into `plink`, and this is now available as a [gist]('https://gist.github.com/philchalmers/4614a7dfd764b4eb65a1') which can either be source manually or sourced with `devtools`:

```r
library(devtools)
source_gist('philchalmers/plink-archived')
```