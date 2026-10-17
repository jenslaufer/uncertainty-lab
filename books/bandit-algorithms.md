# Bandit Algorithms

Tor Lattimore & Csaba Szepesvári — 2020

## Three key theories

1. **Optimism in the face of uncertainty** — In stochastic bandits, act as if each arm is as good as is plausibly consistent with the data. The Upper Confidence Bound (UCB) algorithm does this and achieves logarithmic regret. Regret — the loss against always playing the best arm — is the book's measure of performance.
2. **Adversarial bandits** — When an adversary chooses the rewards, no statistical assumptions hold. Randomized exponential-weighting algorithms such as Exp3 still guarantee sublinear regret. The book develops these alongside online convex optimization (mirror descent, follow-the-regularized-leader).
3. **Lower bounds** — Information-theoretic arguments show how much regret any algorithm must suffer, in the minimax and in the asymptotic (Lai–Robbins) sense. Matching upper and lower bounds prove when an algorithm is optimal. The book extends this to linear, contextual and Bayesian settings, including Thompson sampling.

## Core concepts

1 Bayesian updating, 5 Explore vs. exploit, 6 Information & entropy, 12 Game theory & agents

[Back to sources](../SOURCES.md)
