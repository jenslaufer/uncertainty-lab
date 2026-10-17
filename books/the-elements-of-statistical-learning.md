# The Elements of Statistical Learning

Trevor Hastie, Robert Tibshirani & Jerome Friedman — 2nd ed., 2009

## Three key theories

1. **Bias–variance tradeoff and model complexity** — Prediction error splits into bias, variance, and irreducible noise. Flexible models cut bias but raise variance; the right complexity minimizes test error, not training error. Cross-validation and related methods estimate it.
2. **Regularization and shrinkage** — Penalizing coefficient size trades a little bias for a large drop in variance. Ridge shrinks, the lasso shrinks and selects, and the same idea extends to splines and kernels. Constraint, not freedom, makes high-dimensional models generalize.
3. **Ensembles: boosting, bagging, random forests** — Combining many weak or unstable learners yields strong predictions. Boosting is framed as forward stagewise additive modeling that fits a loss function by gradient steps. Bagging and random forests reduce variance by averaging decorrelated trees.

## Core concepts

10 Optimization & selection, 13 Modeling & its limits

[Back to sources](../SOURCES.md)
