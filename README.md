# Misc_implementations

Those are implementations of algorithms I was not really familiar with but turned out to be fun, usefull and a good way to learn new stats or framework. So those notebooks are a summary of what I understood. Again they should not be used like a ready to go pipeline.

- **Doubly robust estimation of continuous treatment effects for causal inference**. There are some libraries out there in python to do causal inferences when the treatment variable is categorical but not when it is continuous and not for the doubly robust estimation which can be interesting when you don't have a lot of data and matching is not possible... So I implemented one in python from a publication that solves the problem mathematically and proposed also an implementation in R.

- **Group based trajectory modeling**: a bayesian implementation of GBTM (mixture models where data are produced according to different linear models) with pymc3, and so a cool example for using pymc3. I should try the same with pyro.ai later.

- **ECG Auto Encoder Anomaly detection**: ECG Auto Encoder Anomaly detection.ipynb is a notebook where I implemented an auto encoder, a pytorch variational auto encoder and a Pyro.ai variational autoencoder on normal ecg and check if it was able to detect abnormal ecg. It is more an exercise to understand Auto Encoder and how to implement them as well as my first dive into deep probablistic modeling with Pyro.ai. I used 2 images from the awesome blog post : https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73. Be sure to check it out. I provide also another notebook which look at solving the ECG problem with pyro in a more carefull manner rather than just comparison between algos for the sake of comparision. And a notebook that uses an AE and a Pyro VAE for the MNIST dataset.

- **Graph Isomorphism Neural Network based deterministic Auto Encoder** : a notebook where I used pytorch geometric and pytorch lightning to better understand GNN. A lot of fun eventhough I am not too sure of the conclusion or method yet. I am still confident that the results are interesting and meaningfull which gives me confidence about the method I implemented but more reveiw and discussion are needed.(Turned out that graph embedding is still a resaerch question and eventhough the global pooling I am using is not necessarly reversible for the decoder, experts I discussed with still think it is interesting and that I should go back to what is the similarity metric that this approach is embedding from)

- **12 leads ECG** : a more complicated and realistic case of handling ECG data but still bounded to compute capacity of a desktop machine. Right now for classification but hopefully at some point also some generative modeling. This first implementation was also a good opportunity to test SHAP : a library that helps interpreting any models and here in particular DNN.
