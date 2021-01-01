---
layout: default
title: Software
permalink: /software.html
---
Visit our [GitHub page](https://github.com/isrlab) for a full list.

## F-16 Model

[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/F16Model)
This is a Julia package for a nonlinear model of the F16 aircraft. The aerodynamics included in this model come from the NASA Technical Report 1538, Simulator Study of Stall/Post-Stall Characteristics of a Fighter Airplane with Relaxed Longitudinal Static Stability, by Nguyen, Ogburn, Gilbert, Kibler, Brown, and Deal, Dec 1979. The flight dynamics are based on Aircraft Control and Simulations, by Brian Stevens and Frank Lewis, Wiley Inter-Science, New York, 1992.

## Robust Control Toolbox

[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/RobustControl)
This is a Julia implementation of robust control design and analysis algorithms. This is under development. Currently, the toolbox has support for:

1. Definition of linear system objects
1. Plotting of standard responses
1. System interconnections

More features are being added.

## Maximum Entropy Basis Functions

[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/MaximumEntropyBasisFunctions)
Julia package for maximum entropy basis functions. See examples in example/ for generating basis functions and their first derivative in 1D and 2D. The code is dimension agnostic.

The code implements algorithm from the following paper: *Local maximum-entropy approximation schemes: A seamless bridge between finite elements and meshfree methods by M. Arroyo and M. Ortiz*.

## Multibody Dynamics

[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/Multibody-Dynamics)
Julia package for multibody dynamics using [Udwadia-Kalaba](https://en.wikipedia.org/wiki/Udwadia–Kalaba_equation) formulation. This is a fairly complete package with several joint types defined. Many new features are currently being added.

## STEDY

[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/stedy)STEDY is a MATLAB Software for TEnsegrity DYnamics. In this software, the topology of the tensegrity network is described using connectivity matrices, with mass properties of the bars and cables. The dynamics is derived in the Lagrangian framework with non-minimal coordinates and holonomic constraints ([paper](https://rdcu.be/b7jyY)). The software also accounts for errors in numerical integration by providing corrections for constraint violations and drifts in mechanical energy. Please see the [user guide](https://github.com/uqLab/stedy/blob/master/Docs/UserGuide.md) to get started.

## OPTRAGEN
[<img src="assets/images/GitHub-Mark-120px-plus.png"
     alt="GitHubicon"
     style="float: left; margin-right: 10px; height:14pt" />](https://github.com/isrlab/Optragen)
OPTRAGEN is a MATLAB toolbox for solving optimal control problems. Currently, it relies on [SNOPT](https://web.stanford.edu/group/SOL/snopt.htm). Future versions will interface with matlab's fmincon(...).

<!-- #### [Polynomial Chaos](link)
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
* Examples from flight control, structural control, and large-scale distributed systems -->


