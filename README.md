# Smoothing Techniques

Smoothing techniques are frequently used to reduce the variability of the observational data and enhance prediction accuracy, while still providing an adequate fit. In this workshop, we will introduce two popular smoothing methods, kernel smoothing and smoothing splines, from their formulations to the computations. Each method has a smoothing parameter that controls the amount of roughness. We will demonstrate how to choose the optimal tuning parameters from the perspective of variance-bias trade-off. Some examples of how to apply the two methods will be provided.

## Introduction

- Why do we need smoothing techniques?

- What do we loose if we use smoothing techniques?

## Kernel Smoothing Methods

## Smoothing Spline

When fitting a function $f(\cdot)$ to a set of data, the first thing that we want is to find some function that fits the observed data well: that is, we
want the residual sum of squares which measures the goodness of fit, $RSS=\sum_{i=1}^{n} (y_i - f(x_i))^2$, to be small. If this is our only repuirement, then we can even make RSS to zero by simply interpolating all observational data. 

## Reference
Gu, Chong. Smoothing spline ANOVA models. Vol. 297. New York: Springer, 2013.

Hastie, Trevor, et al. The elements of statistical learning: data mining, inference, and prediction. Vol. 2. New York: springer, 2009.

Simonoff, Jeffrey S. Smoothing methods in statistics. Springer Science & Business Media, 2012.

Wahba, Grace. Spline models for observational data. Society for industrial and applied mathematics, 1990.
