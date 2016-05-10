# a2reg : Estimating panel data models with high dimensional fixed effects

## description

The source code implements the conjugate gradient algorithm to solve for the fixed effects of regressions of the following kind:

y_it = x_it \beta + \theta_i + \psi_J(i,t) + e_it

where y_it and x_it are observed, and \beta, \theta, and \psi are to be estimated.

This repository contains stata code, with mata. 

## todos

I didn't have time to implement the nice user interface features such as:

- focusing on the set of non missing observations.
- checking that the set of xs are not perfectly correlated.

## installing

The code can simply be installed by using the SSC software components library at Boston University.

ssc install a2reg

