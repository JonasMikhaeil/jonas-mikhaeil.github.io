---
title: "How to train RNNs on chaotic data?"
collection: publications
permalink: /publication/2021-10-paper-howToTrainRnns-number-1
excerpt: 'Recurrent  neural  networks  (RNNs)  are  wide-spread  machine  learning  tools  formodeling sequential and time series data.  They are notoriously hard to train because their loss gradients backpropagated in time tend to saturate or diverge duringtraining.  This is known as the exploding and vanishing gradient problem.  Previous solutions to this issue either built on rather complicated, purpose-engineered architectures with gated memory buffers, or - more recently - imposed constraints that ensure convergence to a fixed point or restrict (the eigenspectrum of) the recurrence matrix.  Such constraints, however, convey severe limitations on the expressivity of the RNN. Essential intrinsic dynamics such as multistability or chaos are disabled.  This is inherently at disaccord with the chaotic nature of many, if not most, time series encountered in nature and society. Here we offer a comprehensive theoretical treatment of this problem by relating the loss gradients during RNN training to the Lyapunov spectrum of RNN-generated orbits. We mathematically prove that RNNs producing stable equilibrium or cyclic behavior have bounded gradients, whereas the gradients of RNNs with chaotic dynamics always diverge. Based on these analyses and insights, we offer an effective yet simple training technique for chaotic data and guidance on how to choose relevant hyperparameters according to the Lyapunov spectrum.'
date: 'Oct 2021'
venue: 'ArXiv'
paperurl: ''
citation: 'Monfared, Z.*, Mikhaeil, J.* & Durstewitz, D. (2021). How to train RNNs on chaotic data. submitted to
ICLR'
---
This paper is about how to train RNNs on chaotic data.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Citation: Monfared, Z.* , **Mikhaeil, J.*** & Durstewitz, D. (2021). *How to train RNNs on chaotic data*. submitted to ICLR