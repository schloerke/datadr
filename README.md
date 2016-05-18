# datadr: Divide and Recombine in R

[![Build Status](https://travis-ci.org/tesseradata/datadr.svg?branch=master)](https://travis-ci.org/tesseradata/datadr)
[![CRAN](http://www.r-pkg.org/badges/version/datadr)](https://cran.r-project.org/web/packages/datadr/index.html)

datadr is an R package that leverages [RHIPE](https://github.com/tesseradata/RHIPE) to provide a simple interface to division and recombination (D&R) methods for large complex data.

To get started, see the package documentation and function reference located [here](http://tesseradata.github.com/datadr). 

Visualization tools based on D&R can be found [here](https://github.com/tesseradata/trelliscope).

## Installation

```r
# from CRAN:
install.packages("datadr")

# from packages.tessera.io:
options(repos = c(tessera = "http://packages.tessera.io", getOption("repos")))
install.packages("datadr")

# from github:
devtools::install_github("tesseradata/datadr")
```

## License

This software is currently under the BSD license.  Please read the [license](https://github.com/tesseradata/datadr/blob/master/LICENSE.md) document.

## Acknowledgement

datadr development is sponsored by:

- U.S. Department of Defense Advanced Research Projects Agency, XDATA program
- U.S. Department of Homeland Security, Science and Technology Directorate, Homeland Security Advanced Research Projects Agency (HSARPA)
- Pacific Northwest National Laboratory, operated by Battelle for the U.S. Department of Energy, LDRD Program, Signature Discovery and Future Power Grid Initiatives

