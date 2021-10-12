---
title: "How to train RNNs on chaotic data?"
collection: publications
permalink: /publication/2021-10-paper-howToTrainRnns-number-1
excerpt: 'Recurrent  neural  networks  (RNNs)  are  wide-spread  machine  learning  tools  formodeling sequential and time series data.  They are notoriously hard to train be-cause their loss gradients backpropagated in time tend to saturate or diverge duringtraining.  This is known as the exploding and vanishing gradient problem.  Previ-ous solutions to this issue either built on rather complicated, purpose-engineeredarchitectures with gated memory buffers, or - more recently - imposed constraintsthat ensure convergence to a fixed point or restrict (the eigenspectrum of) the re-currence matrix.  Such constraints, however, convey severe limitations on the ex-pressivity of the RNN. Essential intrinsic dynamics such as multistability or chaosare disabled.  This is inherently at disaccord with the chaotic nature of many, ifnot most, time series encountered in nature and society. Here we offer a compre-hensive theoretical treatment of this problem by relating the loss gradients duringRNN training to the Lyapunov spectrum of RNN-generated orbits.   We mathe-matically prove that RNNs producing stable equilibrium or cyclic behavior havebounded gradients, whereas the gradients of RNNs with chaotic dynamics alwaysdiverge.  Based on these analyses and insights, we offer an effective yet simpletraining technique for chaotic data and guidance on how to choose relevant hyper-parameters according to the Lyapunov spectrum.'
date: 'Oct 2021'
venue: 'ArXiv'
paperurl: ''
citation: '...'
---
This paper is about how to train RNNs on chaotic data.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).