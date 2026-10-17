# Deep Learning

Ian Goodfellow, Yoshua Bengio & Aaron Courville — 2016

## Three key theories

1. **Representation learning through depth** — Deep networks learn a hierarchy of concepts, each defined by simpler ones below it. Distributed representations let many features combine to describe exponentially many inputs. Depth lets the machine discover the features humans once engineered.
2. **Learning as gradient-based optimization** — Training minimizes a loss by stochastic gradient descent, with gradients computed by back-propagation through a computational graph. Non-convex objectives, poor conditioning, and vanishing gradients make optimization the central practical difficulty. Initialization, momentum, adaptive learning rates, and normalization address it.
3. **Regularization for generalization** — The goal is low error on unseen data, not on training data. Weight decay, dropout, early stopping, data augmentation, and parameter sharing restrict effective capacity. The manifold hypothesis explains why learning in high dimensions works at all.

## Core concepts

10 Optimization & selection, 13 Modeling & its limits

[Back to sources](../SOURCES.md)
