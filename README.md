# Markov Chain Monte Carlo Course Notes

The goal is to write up notes from a Markov chain Monte Carlo course I've taught on a few occasions.  The intended audience consists of researchers new to MCMC theory and methods.  The foundations of MCMC will be emphasized, not necessarily the most cutting edge research methods and algorithms, at least at first.   Updates will be irregular and all files should be considered drafts that may change substantially.

[Monte Carlo])(Monte Carlo/gofmc.pdf)
  * Introduction
    * Motivating examples
  * Monte Carlo method
    * Producing a sample  
      * Inversion
      * Accept-Reject
      * Ratio of Uniforms
      * Linchpin Variables
  * Estimation Theory for Monte Carlo
    * Monte Carlo Estimation
    * Monte Carlo Error
    * Generalized Monte Carlo Error
    * Confidence Regions
 
* Markov Chain Monte Carlo
  * Markov Chains
    * Markov Kernels
    * Invariance
    * Combining Kernels
    * Stochastic Stability
  * Constructing MCMC Algorithms
    * Metropolis-Hastings
    * Component-wise Updates
      * Linchpin Variables
      * Gibbs Samplers
      * Conditional Metropolis-Hastings
  * Convergence
    * Total variation
    * Wasserstein
    * Stochastic Stability of MCMC
    * Minorization, Coupling, and Split Chain
  * Estimation
    * LLN
    * CLT (Means, quantiles, and combo)
    * Mixing Processes
    * Rates of Convergence
  * Convergence Rates in Practically Relevant Settings
    * Comparison Theorems
    * Drift and Minorization
    * Upper and Lower Bounds
    * Examples and more examples
    * Variable Transformation
  * Monte Carlo Error
    * Batch Means
    * Spectral Variance
    * ESS
    * Terminating the Simulation
   
