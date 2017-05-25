# a2reg : Estimating panel data models with high dimensional fixed effects

## description

The source code implements the conjugate gradient algorithm to solve for the fixed effects of regressions of the following kind:

<a href="https://www.codecogs.com/eqnedit.php?latex=y_{it}&space;=&space;x_{it}&space;\beta&space;&plus;&space;\theta_i&space;&plus;&space;\psi_{J(i,t)}&space;&plus;&space;e_{it}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y_{it}&space;=&space;x_{it}&space;\beta&space;&plus;&space;\theta_i&space;&plus;&space;\psi_{J(i,t)}&space;&plus;&space;e_{it}" title="y_{it} = x_{it} \beta + \theta_i + \psi_{J(i,t)} + e_{it}" /></a>

where y_it and x_it are observed, and \beta, \theta, and \psi are to be estimated.

This repository contains stata code. Matrix algebra coded in Mata.

## todos

Most code is just wrapping a good algorithm to make it user-friendly. I have neither time nor incentives to implement the nice user interface features such as:

   - focusing on the set of non missing observations.
   - checking that the set of xs are not perfectly correlated.

## installing

The code can simply be installed by using the SSC software components library at Boston University.

_ssc install a2reg_

