# Reinforcement Learning: An Introduction

Richard Sutton & Andrew Barto — 2nd ed., 2018

## Three key theories

1. **Finite Markov decision processes** — An agent acts in an environment, observes states and receives rewards; its goal is to maximize cumulative reward (the reward hypothesis). Value functions and the Bellman equations formalize how good states and actions are. The trade-off between exploration and exploitation runs through the whole problem.
2. **Generalized policy iteration** — Almost every method interleaves two processes: policy evaluation, which estimates the value of the current policy, and policy improvement, which acts greedily on that estimate. Dynamic programming, Monte Carlo and TD methods all fit this pattern. They differ in how they evaluate.
3. **Temporal-difference learning** — TD methods update estimates from other estimates (bootstrapping) without a model of the environment. They combine the sampling of Monte Carlo with the bootstrapping of dynamic programming. TD, Sarsa and Q-learning form the book's core, extended by n-step methods, eligibility traces and function approximation.

## Core concepts

5 Explore vs. exploit, 7 Feedback & dynamical systems, 10 Optimization & selection, 12 Game theory & agents

[Back to sources](../SOURCES.md)
