# Gaussian MLP Ensemble for Predictive Uncertainty Estimation:
Implementation of the paper "Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles"[https://arxiv.org/abs/1612.01474]

Code originally from https://github.com/dougbrion/pytorch-deep-ensembles/tree/main, adapted for own experiments.

The models have 1 hidden layer, and a tuple output of (mean, variance). The loss function is the Negative log likelihood described in the paper.  

`conda env create -f environment.yml`
