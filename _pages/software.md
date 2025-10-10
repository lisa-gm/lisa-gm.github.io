---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## DALIA

DALIA is a probabilistic programming framework for Bayesian statistical learning. It is based on the methodology of integrated nested Laplace approximations (INLA) and applicable to latent Gaussian models. The Python-based framework supports distributed memory parallelism and GPU-acceleration. 

[Link to the Github](https://github.com/dalia-project/DALIA).


## Serinv

Serinv is a selected solver library for structured sparse matrices. It is one of the computational backends of DALIA. Serinv contains various routines for the decomposition, selected inversion and solve of linear systems of equations. It is Python-based, contains shared and distributed memory algorithms and offers GPU backends.
  
[Link to the Github](https://github.com/vincent-maillou/serinv).


##  <h2>\(\text{INLA}_\text{DIST}\)</h2>

$\text{INLA}_\text{DIST}$ provides a scalable implementation the INLA methodology focusing on spatial and spatio-temporal modeling. It leverages the stochastic partial differential equations (SPDE) approach to provide an efficient framework for performing inference, leveraging sparse representations of the underlying processes. 

[Github](https://github.com/lisa-gm/INLA_DIST)


### Sparse Quadratic Inverse Covariance Matrix Estimation (SQUIC)

SQUIC is a package for large-scale sparse precision matrix estimation. It utilizes a second order method for solving the $\ell_1$-regularized maximum likelihood problem. The repository offers R and Python interfaces for Mac OS and Linux while the core library is written in C++ and parallelized using OpenMP.

[Github](https://www.gitlab.ci.inf.usi.ch/SQUIC)