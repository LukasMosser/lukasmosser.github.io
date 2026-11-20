---
title: "Stochastic Seismic Waveform Inversion Using Generative Adversarial Networks as a Geological Prior"
collection: publications
permalink: /publication/2018-Stochastic.md
excerpt: 'We combine a generative adversarial network (GAN) representing an a priori model that creates subsurface geological structures and their petrophysical properties, with the numerical solution of the PDE governing the propagation of acoustic waves within the earths interior. We perform Bayesian inversion using an approximate Metropolis-adjusted Langevin algorithm (MALA) to sample from the posterior given seismic observations.'
date: 2019-11-15
venue: 'Mathematical Geosciences'
paperurl: 'https://doi.org/10.1007/s11004-019-09832-6'
citation: 'Mosser, L., Dubrule, O., & Blunt, M. J. (2020). Stochastic Seismic Waveform Inversion Using Generative Adversarial Networks as a Geological Prior. Mathematical Geosciences, 52(1), 53-79.'
---
We present an application of deep generative models in the context of partial-differential equation (PDE) constrained inverse problems. We combine a generative adversarial network (GAN) representing an a priori model that creates subsurface geological structures and their petrophysical properties, with the numerical solution of the PDE governing the propagation of acoustic waves within the earth's interior. We perform Bayesian inversion using an approximate Metropolis-adjusted Langevin algorithm (MALA) to sample from the posterior given seismic observations. Gradients with respect to the model parameters governing the forward problem are obtained by solving the adjoint of the acoustic wave equation. Gradients of the mismatch with respect to the latent variables are obtained by leveraging the differentiable nature of the deep neural network used to represent the generative model. We show that approximate MALA sampling allows efficient Bayesian inversion of model parameters obtained from a prior represented by a deep generative model, obtaining a diverse set of realizations that reflect the observed seismic response.

[Read the paper here](https://doi.org/10.1007/s11004-019-09832-6) · [arXiv preprint](https://arxiv.org/abs/1806.03720)
