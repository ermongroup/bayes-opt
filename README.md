# bayes-opt

This repository contains code used in the UAI 2016 paper "Sparse Gaussian processes for Bayesian optimization," and implements the weighted online GP described therein. It includes (partial and potentially modified) implementations of SPGP (Snelson and Ghahramani) and Online Sparse GPs (Lehel Csato), translated to Python from the original work of the respective authors. 

Also included is a simple implementation of Bayesian optimization, as well as a demonstration on a toy problem in example_script and a script that tests weighted and unweighted online GPs on LCLS data. The LCLS data used for our experiments is much too large to include in the repository, so we include a small subset taken at a particular electron energy.

The code here is unoptimized (quite slow in places, though nothing as written should take longer than a few minutes to run) and lacks a great deal of features and safety measures. Feel free to report any problems beyond these.
