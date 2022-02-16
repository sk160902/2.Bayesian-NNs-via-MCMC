# 2.Bayesian-NNs-via-MCMC
A dataset df was created and was spilt into train and test sets
Prior,Posterior and likeliohood functions were implemented using an array of evenly spaced numbers
The Gaussian Process Regression model was built and the MlP weights MLP weights that have posterior probability was sampled by implementing the Hamiltonian Monte Carlo(HMC) Procedure OF THE MCMC
The samples were then observed using the marginal distribution of parameters by means of a function wherein the changes of noise variance with respect to signal variance and lengthscale was observed
The posterior function was then plotted after sampling the MLP weights that had posterior probability
Finally,the sampled sets of weights was implemented by using the random forest classifier function under ensemble prediction.
