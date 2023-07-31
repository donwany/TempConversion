# TempConversion
Temperature Conversion R Package

### Install
```sh
install.packages("devtools")
install.packages("roxygen2")


library(devtools);
load_all("."); # Working directory should be in the package TempConverter_package


library(roxygen2); # Read in the roxygen2 R package
roxygenise();      # Builds the help files

```

### Usage
```r
library(devtools)

install_github("donwany/TempConversion")

library("TempConversion"")

```
### Example
```r
F_to_C(90)
C_to_F(32)
```




