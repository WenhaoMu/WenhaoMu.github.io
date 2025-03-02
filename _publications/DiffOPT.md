---
title: "Diffusion models as constrained samplers for optimization with unknown constraints"
collection: publications
permalink: /publication/DiffOPT
excerpt: '**Wenhao Mu\***, Lingkai Kong\*, Yuanqi Du\*, Kirill Neklyudov, Valentin De Bortoli, Dongxia Wu, Haorui Wang, Aaron Ferber, Yi-An Ma, Carla P Gomes, Chao Zhang'
date: 2025-2-1
venue: 'Artificial Intelligence and Statistics (AISTATS)'
---
[paper](https://arxiv.org/abs/2402.18012)

# abstract:
Addressing real-world optimization problems becomes particularly challenging when analytic objective functions or constraints are unavailable. While numerous studies have addressed the issue of unknown objectives, limited research has focused on scenarios where feasibility constraints are not given explicitly. Overlooking these constraints can lead to spurious solutions that are unrealistic in practice. To deal with such unknown constraints, we propose to perform optimization within the data manifold using diffusion models. To constrain the optimization process to the data manifold, we reformulate the original optimization problem as a sampling problem from the product of the Boltzmann distribution defined by the objective function and the data distribution learned by the diffusion model. Depending on the differentiability of the objective function, we propose two different sampling methods. For differentiable objectives, we propose a two-stage framework that begins with a guided diffusion process for warm-up, followed by a Langevin dynamics stage for further correction. For non-differentiable objectives, we propose an iterative importance sampling strategy using the diffusion model as the proposal distribution. Comprehensive experiments on a synthetic dataset, six real-world black-box optimization datasets, and a multi-objective molecule optimization dataset show that our method achieves better or comparable performance with previous state-of-the-art baselines.
