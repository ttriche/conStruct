
## Test environments
* local OS X install R 3.5.0

## R CMD check results
There were no ERRORs or WARNINGs

There were 2 NOTES:

* checking for GNU extensions in Makefiles ... NOTE
  GNU make is a SystemRequirements.

Explanation: GNU make is required for packages that 
depend on rstan and which are developed using rstantools. 
The requirement is noted in the DESCRIPTION file.

* checking installed package size ... NOTE
  installed size is  5.2Mb
  sub-directories of 1Mb or more:
    libs   4.5Mb

Explanation: This package has a large installed library 
size because it uses the Stan MCMC library as a backend, 
and the C++ Stan models included in the package are 
compiled upon installation. Although the resultant libraries 
are large, the size of the pre-installed package is small.


## Downstream dependendencies

* There are currently no downstream dependencies for this package.