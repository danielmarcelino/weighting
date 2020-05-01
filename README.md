# Model-based weighting
This has the codes for the simulation and application of model-based weighting in the context of national surveys.

An initial draft of MrP improvement tentative is also included. 


# Installing required software

To run the code you will need to install a special branch of the __rstanarm__ package using the code below. 
This will take several minutes to install because some C++ code needs to be compiled. 

```r
if (!require(devtools)) {
  install.packages("devtools")
  library(devtools)
}
install_github("stan-dev/rstanarm", ref = "structured_prior_merge", args = "--preclean", build_vignettes = FALSE)
```
