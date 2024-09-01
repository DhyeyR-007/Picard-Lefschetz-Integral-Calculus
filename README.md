# plind.py Documentation

## Overview
**plind.py** (Picard-Lefschetz Integration in N-Dimensions) is a Python package that facilitates the application of the Picard-Lefschetz method to calculate integrals of highly oscillatory functions in multiple dimensions.

## Purpose
This package is specifically designed for users who need to compute integrals of the form:

$$I = \int_\Omega \text{d}^n\mathbf{x}\exp(i S(\mathbf{x}; \mathbf{\mu}))$$

These types of integrals are commonly encountered in quantum mechanics and wave optics, and pose significant challenges for traditional numerical methods due to the presence of rapid oscillations.

Picard-Lefschetz (PL) theory offers a solution to this problem by analytically continuing the integration domain to complex space $\mathbb{C}^n$, deforming the domain according to specific rules, and performing the integration over this newly defined region.

The **plind.py** package provides a Python-based implementation of this method.

## Example Implementation
Sample usage and implementation can be found in ipynb notebook.

## Installation
To use plind.py, run pip install plind.



## Refer for more info
https://p-lpi.github.io/




