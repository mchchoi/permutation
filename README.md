# Improving the convergence of Markov chains via permutations and projections

**Authors:** Michael C.H. Choi, Max Hird, and Youjia Wang  
**arXiv:** [https://arxiv.org/abs/2411.08295](https://arxiv.org/abs/2411.08295)

This repository contains the code for the experiments in the paper *Improving the convergence of Markov chains via permutations and projections*. We compare standard Metropolis-Hastings samplers with projection samplers on three models:

- Ising model on the line
- Edwards-Anderson spin glass
- Blume-Capel model

## Example: Ising model on the line with d = 50

Below is an animation comparing the standard Metropolis-Hastings sampler with the adaptive projection sampler. The magnetization over time is shown at the bottom.

![Ising animation](ising_config_with_magnetization.gif)

We thank Zheyuan Lai for computational assistance.
