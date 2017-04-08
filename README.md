# PEcAn_2017
# In order to synthesize large-scale data with models, PEcAn provides a Bayesian data assimilation framework. PEcAn’s data assimilation module uses Metropolis-Hastings MCMC algorithm implemented in R and also supports external packages that provide other samplers. The issue is that using the algorithm takes time, considerably so for slower models, therefore algorithms that can be parallelized and make use of GPU programming are desirable.
# Implement rejection sampling or Sequential Monte Carlo (SMC) sampling in data assimilation module and transform into GPU code.
