# Misc_implementations

Those are implementations of algorithm I was not really familiar with but turned out to be fun, usefull and a good way to learn new stats or framework. So those notebook arez a summary of what I understood. Again they should not be used like a ready to go pipeline.

-**Doubly robust estimation of continuous treatment effects for causal inference**. There are some libraries out there in python to do causal inferences when the treatment variable is categorical but not when it is continuous and not for the doubly robust estimation which can be interesting when you don't have a lot of data and matching is not possible... So I implemented one in python from a publication that solves the problem mathematically and proposed also an implementation in R.

-**Group based trajectory modeling**: a bayesian implementation of GBTM (mixture models where data are produced according to different linear models) with pymc3, and so a cool example for using pymc3. I should try the same with pyro.ai later.
