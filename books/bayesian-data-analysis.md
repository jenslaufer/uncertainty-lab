# Bayesian Data Analysis

Andrew Gelman et al. — 3rd ed., 2013

## Three key theories

1. **Hierarchical models** — Exchangeable parameters get a common population distribution, whose hyperparameters are estimated from the data. Groups borrow strength from each other through partial pooling. This is the book's central modeling framework.
2. **Model checking with posterior predictive checks** — Fitting a model is not the end: simulate replicated data from the posterior and compare it with the observed data. Systematic discrepancies reveal misfit. Bayesian workflow cycles through building, checking, and expanding models.
3. **Posterior simulation (MCMC)** — Realistic posteriors have no closed form, so inference relies on drawing samples. Gibbs sampling, Metropolis, and Hamiltonian Monte Carlo make complex models computable. Convergence diagnostics decide whether the draws can be trusted.

## Core concepts

1 Bayesian updating, 13 Modeling & its limits

[Back to sources](../SOURCES.md)
