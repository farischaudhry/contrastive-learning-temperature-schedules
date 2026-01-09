# Convergence of Anisotropic Langevin-Based Temperature Annealing for Contrastive Learning

This repository contains the JAX and NumPy code to reproduce the empirical results for the paper of the same name.

## Overview

The code implements a simulation of the anisotropic Langevin Stochastic Differential Equation as described in the paper. It is used to validate the paper's theoretical claims in a controlled, low-dimensional setting.

Specifically, the experiments simulate the dynamics of a minimal contrastive learning problem with **N=4 embeddings evolving on a 3-dimensional sphere**. The code is designed to generate the main figures presented in the paper:

* **Figure 1:** The success probability of convergence as a function of the annealing rate `c`.
* **Figure 2:** The distribution of first hitting times for different annealing schedules.

## Setup

The required dependencies are listed in `requirements.txt`. You can install them using pip:

```bash
pip install -r requirements.txt
```
