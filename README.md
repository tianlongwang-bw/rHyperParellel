# rHyperband

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/rHyperband)](http://cran.r-project.org/package=rHyperband)
[![CRAN Downloads](http://cranlogs.r-pkg.org/badges/rHyperband)](http://cran.r-project.org/package=rHyperband)
![CRAN Downloads Total](http://cranlogs.r-pkg.org/badges/grand-total/rHyperband?color=brightgreen)
Linux/Mac: [![Build Status](https://travis-ci.org/yanyachen/rHyperband.svg)](https://travis-ci.org/yanyachen/rHyperband)
Windows: [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/yanyachen/rHyperband?branch=master&svg=true)](https://ci.appveyor.com/project/yanyachen/rHyperband)

Hyperband algorithm for Hyperparameter Optimization  

A Pure R implementation of Hyperband algorithm for Hyperparameter Optimization.  

This is the Bridgewater version that has a parallel option. See: https://cran.r-project.org/web/packages/doParallel/vignettes/gettingstartedParallel.pdf

To install:  
* the stable version from [CRAN](http://cran.r-project.org/web/packages/rHyperband/index.html):  
```r
install.packages("rHyperband")
```

* the latest development version:  
```r
devtools::install_github("tianlongwang-bw/rHyperParellel")
```

Because of authentication issues, you may need to download the zip file, and then create a tarball, and then install it.
```unzip rHyperband-master.zip
R CMD build --force rHyperband-master
sudo R CMD INSTALL rHyperband_1.0.0-1.tar.gz
```
