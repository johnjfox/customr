## Introduction

TBD

### Applications

TBD

### Specific Application: Customer Lifetime Value

TBD

## Installation

You'll need to install ``rstan`` first. Go to [http://mc-stan.org](http://mc-stan.org) and follow the instructions for your platform. The biggest challenge is getting a C++ compiler configured to work with your installation of R. The instructions at [https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started) are thorough, but there are several steps to take. If you're wondering why you need rstan, it's because most of the models have been implemented in stan code. 

Once you're convinced that stan / rstan has been installed corectly, you can install ``customr`` from within R using:

```
install.packages(c("devtools"))
library(devtools)
devtools::install_github("johnjfox/customr")
```

This installation will probably take longer than expected. That's because the stan models are being compiled. This should only happen once though.

More than likely, if there are problems during the installation it will be related to your stan/rstan installation. See the manual linked above for some hints about getting ``rstan`` installed and check the RStan section of the website at ``mc-stan.org`` for the latest information on RStan.

## Contributing

TBD

## Documentation and tutorials

TBD


## Questions? Comments? Requests?

TBD

## Main Articles

TBD

## More Information

1. [Papers](http://mktg.uni-svishtov.bg/ivm/resources/Counting_Your_Customers.pdf), lots of [papers](http://brucehardie.com/notes/009/pareto_nbd_derivations_2005-11-05.pdf).
1. R implementation of several of the included models is called [BTYD](http://cran.r-project.org/web/packages/BTYD/index).
1. A Python implementation of several of the models is available at 
[lifetimes](https://github.com/CamDavidsonPilon/lifetimes).
1. A great set of resources tied to Bayesian analysis, including a very nice package, is at 
[rethinking](https://github.com/rmcelreath/rethinking)
1. [Bruce Hardie's Website](http://brucehardie.com/)
1. [STAN](http://mc-stan.org)