# Misc_implementations

Those are implementations of algorithm I was not really familiar with but turned out to be fun, usefull and a good way to learn new stats or framework. So those notebook arez a summary of what I understood. Again they should not be used like a ready to go pipeline.

- **Doubly robust estimation of continuous treatment effects for causal inference**. There are some libraries out there in python to do causal inferences when the treatment variable is categorical but not when it is continuous and not for the doubly robust estimation which can be interesting when you don't have a lot of data and matching is not possible... So I implemented one in python from a publication that solves the problem mathematically and proposed also an implementation in R.

- **Group based trajectory modeling**: a bayesian implementation of GBTM (mixture models where data are produced according to different linear models) with pymc3, and so a cool example for using pymc3. I should try the same with pyro.ai later.

- **ECG Auto Encoder Anomaly detection**: a notebook where I implemented an auto encoder, a pytorch variational auto encoder and a Pyro.ai variational autoencoder on normal ecg and check if it was able to detect abnormal ecg. It is more an exercise to understand Auto Encoder and how to implement them as well as my first dive into deep probablistic modeling with Pyro.ai. I used 2 images from the awesome blog post : https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73. Be sure to check it out.
