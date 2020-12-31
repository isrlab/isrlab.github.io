---
layout: default
title: Software
permalink: /software.html
---

### 1. STEDY
[STEDY](https://github.com/uqLab/stedy) is a MATLAB Software for TEnsegrity DYnamics. In this software, the topology of the tensegrity network is described using connectivity matrices, with mass properties of the bars and cables. The dynamics is derived in the Lagrangian framework with non-minimal coordinates and holonomic constraints ([paper](https://www.researchgate.net/publication/328676032_A_Lagrangian_Formulation_for_Constrained_Multibody_Dynamics_in_Tensegrity_Systems)). The software also accounts for errors in numerical integration by providing corrections for constraint violations and drifts in mechanical energy. Please see the [user guide](https://github.com/uqLab/stedy/blob/master/Docs/UserGuide.md) to get started.

### 2. OPTRAGEN
[OPTRAGEN](https://github.com/uqLab/Optragen) is a MATLAB toolbox for solving optimal control problems. Currently, it relies on [SNOPT](https://ccom.ucsd.edu/~optimizers/software.html#snopt), which can be downloaded from [here](https://ccom.ucsd.edu/~optimizers/downloads.php). Future versions will interface with matlab's fmincon(...). 

<!--
#### [F-16 Model](link)
A full nonlinear model of the F-16 airplane with matlab scripts for trimming, linearizing, and designing controllers.

#### [Polynomial Chaos](link)
Matlab scripts for applying polynomial chaos theory to propagate uncertainty in dynamical systems. A python version is also in the making. Relies on symbolic computing toolbox. 

#### [Particle based Uncertainty Quantification in Dynamical Systems](link)
* MCMC, SMC, Sampling in Convex Sets
* Transfer Operator: Fokker-Planck-Kolmogorov, Frobenius Perron
* Bayesian and optimal transport framework

#### [Convex Optimization Solvers for Massively Parallel Machines](link)
We make use of lazy synchronization and asynchronous updates across processing elements to overcome synchronization bottlenecks in massively parallel computing machines. Our QP solver achieves [160x](https:doi.org/10.13140/RG.2.1.3167.2729) speedup than synchronized parallel implementations. [OpenMP](http://openmp.org/wp/) (shared memory) and [OpenMPI](https://www.open-mpi.org/) (distributed memory) versions are available. We are also porting it to [Julia](http://julialang.org/). Solvers for other convex problems are also being developed. Stay tuned!

#### [Control System Design Toolbox](link)
* LMI based synthesis of robust control systems (using [cvx](http://cvxr.com/cvx/))
* H2, Hinf, LPV controller and estimator designs
* Probabilistic and worst-case uncertainty
* Control theoretic systems engineering
* Examples from flight control, structural control, and large-scale distributed systems
-->

