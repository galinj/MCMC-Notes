# Markov Chain Monte Carlo Course Notes

The goal is to write up notes from a Markov chain Monte Carlo course I've taught on a few occasions.  The intendend audience consists of researchers new to MCMC theory and methods.  Thus the foundations of MCMC will be emphasized, not necessarily the most cutting edge research methods.   Updates will be irregular.

* Monte Carlo
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
    * Choosing the Proposal
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
    * Upper and Lower Bounds
    * Comparison Theorems
  * Convergence Rates in Practically Relevant Settings
    * Drfit and Minorization
    * Examples and more examples
    * Variable Transformation
  * Monte Carlo Error
    * Batch Means
    * Spectral Variance
    * ESS
    * Terminating the Simulation
   
