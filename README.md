# plind.py Documentation

## Introduction
plind.py (Picard-Lefschetz Integration in N-Dimensions) is a Python package that implements the Picard-Lefschetz method for integrating highly oscillatory functions in any number of dimensions. 

## Description
This code is for people interested in computing integrals of the form
$$I=\int_\Omega \text{d}^n\mathbf{x}\exp i S(\mathbf{x}\;\mathbf{\mu}).$$ 
These integrals occur in quantum theory and wave optics. 
Such integrals are not possible to do using traditional numerical methods due to their highly oscillatory nature. 

However, Picard-Lefschetz (PL) theory gives a recipe for computing them by analytically continuing the integration domain to $\mathbb{C}^n$, deforming the integration domain according to certain rules, then integrating on the new domain. 
This package is an implementation of the PL algorithm in Python. 

For details, see papers in the [additional information](#additional-information) section. 

## Install
To use plind.py, run `pip install plind`.

## Use
To use the code, follow the examples in `Example Notebook.ipynb`. 

## Refer for more info
https://p-lpi.github.io/




