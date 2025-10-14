---
title: "Full Covariance Matrix for Swarm 4 monthly GVOs"
date: 2023-09-01
author: "Chris Finlay"
draft: false
---

Link to a [full data error covariance matrix](http://www.spacecenter.dk/files/magnetic-models/GVO/COV_GVO_4mon_SV_0101.txt) for the 4-monthly GVO SV product.

Format is ascii, Covariance matrix of size 900x900 (900= 3 components at 300 GVOs) order as in GVO `.cdf` files.

If a covariance matrix for the core field is required, assuming uncorrelated errors in time one can use the above SV matrix (derived from annual differences of the core field) scaled by a factor 0.5.

This was derived by the following procedure:

1. Load 4 monthly GVO product, core field or SV series
2. Remove large outliers w.r.t. CHAOS-7.15 field model
3. Compute a Gaussian Process fit to each component at each GVO location (squared exponential kernel).
4. Subtract this fit from observations.
5. Standardise the resulting residuals by removing the mean value and dividing by the standard deviation of the residuals from each component at each GVO.
6. Removed all time epochs with gaps in global coverage, except when only GVO was missing, in which case the missing value was replaced by zero.
7. Compute the non-linear Ledoit-Wolf estimator of the covariance matrix ([Ledoit and Wolf, 2020](https://www.jstor.org/stable/27028732)) which results in a valid (symmetric, positive definite) covariance matrix.

The Ledoit-Wolf nonlinear shrinkage estimator is designed for estimating large covariance matrices. It is based on a minimum variance criteria and involves retaining all eigenvectors of the empirical covariance matrix but shrinking the eigenvalues based on a nonlinear analytic function of the eigenvalues, based on results from random matrix theory ([Ledoit and Wolf, 2020](https://www.jstor.org/stable/27028732)).

Contact: Chris Finlay, cfinlay at space.dtu.dk 