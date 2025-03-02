---
title: "Two Birds with One Stone: Enhancing Uncertainty Quantification and Interpretability with Graph Functional Neural Process"
collection: publications
permalink: /publication/twobirds
excerpt: 'Lingkai Kong, Haotian Sun, Yuchen Zhuang, Haorui Wang, **Wenhao Mu**, Chao Zhang'
date: 2024-2-1
venue: 'Artificial Intelligence and Statistics (AISTATS)'
---
[paper](https://proceedings.mlr.press/v238/kong24a.html)

# abstract:
Graph neural networks (GNNs) are powerful tools on graph data. However, their predictions are mis-calibrated and lack interpretability, limiting their adoption in critical applications. To address this issue, we propose a new uncertainty-aware and interpretable graph classification model that combines graph functional neural process and graph generative model. The core of our method is to assume a set of latent rationales which can be mapped to a probabilistic embedding space; the predictive distribution of the classifier is conditioned on such rationale embeddings by learning a stochastic correlation matrix. The graph generator serves to decode the graph structure of the rationales from the embedding space for model interpretability. For efficient model training, we adopt an alternating optimization procedure which mimics the well known Expectation-Maximization (EM) algorithm. The proposed method is general and can be applied to any existing GNN architecture. Extensive experiments on five graph classification datasets demonstrate that our framework outperforms state-of-the-art methods in both uncertainty quantification and GNN interpretability. We also conduct case studies to show that the decoded rationale structure can provide meaningful explanations.

