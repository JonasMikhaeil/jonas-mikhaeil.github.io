---
title: "SVAE and invariant properties of dynamical systems"
excerpt: "Invariant properties of dynamical systems as evaluation measures for dynamical systems reconstruction and as loss criterium to improve the training of sequential variational autoencoder"
collection: portfolio
---

Supervisor: Daniel Durstewitz

Research on invariant properties of dynamical systems with the goal of developing new evaluation measures for dynamical systems reconstruction and to improve improve training of sequential variational autoencoders. Local measures of agreement between generated dynamics and observations, such as ahead predictions, can be misleading, especially if the underlying dynamics are chaotic. In this case initially close trajectories diverge exponentially fast even if the underlying dynamics have been reconstructed properly. It is thus paramount to use invariant properties of the dynamical system, such as the attractor geometry, to compare the dynamics globally. I extensively helped in the development of two such measures, a Kullback Leibler divergence measuring the similarity of the probability distribution over state space and a power-spectrum correlation to compare the global temporal behaviour. With these measures and a theorem about the conditions for the boundedness of a dendritic RNN, I contributed to the paper *Tractable dendritic RNNs for identifying unknown nonlinear dynamical systems,* which is currently under review for ICLR.
