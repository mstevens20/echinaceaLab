## Useful R functions for Echinacea Project lab activities.

## Installation

You can install then use the **devtools** package to install the development version. Run this code:

```r
install.packages("devtools")
library("devtools")
install_github("stuartWagenius/echinaceaLab")
library("echinaceaLab")
?echinaceaLab
```
Alternatively, you can download the [zip ball](https://github.com/stuartWagenius/echinaceaLab/zipball/master) and run `utils:::menuInstallLocal()` then `library(echinaceaLab)`. This works on Windows machines.

Mac users can download the [tar ball](https://github.com/stuartWagenius/echinaceaLab/tarball/master), decompress and run `R CMD INSTALL` on it.



For more information, visit the Echinacea Project website: http://echinaceaProject.org/.

## NEWS

2015-04-15
This R package now has a dataframe of the heads harvested from p1 and p2 in 2014. Function check.batch can now check batches from 2012, 2013 and 2014.

2014-02-28
This R package now has a dataframe of the heads harvested from cg1 in 2013. Function check.batch can now check batches from 2012 and 2013.

2013-04-12
This R package now has functions for managing scan files, including checking validity of filenames compared to the 2012 harvest list.

2013-04-12
This R package now has a dataframe of the heads harvested from cg1 in 2012.

2013-04-11
This R package now has documentation for each function, at least a little bit.

2013-01-12
This R package now has a function to visualize growth chamber settings and performance. 

2012-12-11
This R package now has functions to manage datasets with twist-tie fields. 

2012-11-30
This R package has functions to manage mass files generated by our automated Mettler-Toledo balance. 


