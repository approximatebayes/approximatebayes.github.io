## Projects

#### Deep Generative models for drug discovery

Deep generative models such as VAEs and GANs have shown remarkable results in maping high dimensional input data to low dimensional latent space. By representing molecules as graphs, we propose to learn an autoencoder over the molecular space and use the latent space to discover new molecules with desried properties.  We propose training a dynamical system which can learn the implicit chemical rules while generating molecules. 

#### Bayesian Deep Ensembles using Stein Variational Gradient Descent

Deep Ensembles are well callibrated and have shown to outerperform bayesian sampling methods. Stein variational inference provides a natural framework of using ensembles to perform variatinal inference. Stein variational gradient descent uses kernel over parameters to ensure particles explore different modes. Kernels are infeasible over deep networks with very large parameter space and we propose various approximations to allow use of stein variational inference over deep neural networks.