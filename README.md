# DistrNN.jl

Available upon request. The code will be available to public when the publication process is finished.

The code has been developed in Julia accompanying the Barunik and Hanus (2022) paper, and provides estimation of probability distributions using *distributional deep learning* introduced in

Baruník, J. and Hanus, L. (2022): *Taming data-driven probability distributions*, manuscript [available here for download](https://barunik.github.io)

**For now**, please refer to the code peraining to a special case for hourly electricity prices. See [Learning Probability Distributions of Day-Ahead Electricity Prices](https://github.com/luboshanus/DistrNNEnergy.jl).

## Software requirements

Install [Julia](http://julialang.org/) version 1.6.7 or newer and with the first use of this code install the same version of packages with which the projects is built and work in the environment of the project as

```julia
using Pkg
Pkg.activate(".") # activating project in its directory
Pkg.instantiate() # installing packages with which versions the project is built
```
