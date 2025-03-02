---
title: "DF2: Distribution-Free Decision-Focused Learning"
collection: publications
permalink: /publication/df2
excerpt: 'Lingkai Kong, **Wenhao Mu**, Jiaming Cui, Yuchen Zhuang, B Aditya Prakash, Bo Dai, Chao Zhang'
date: 2023-5-1
venue: 'preprint'
---
[paper](https://arxiv.org/abs/2308.05889)

# abstract:
Decision-focused learning (DFL) has recently emerged as a powerful approach for predict-then-optimize problems by customizing a predictive model to a downstream optimization task. However, existing end-to-end DFL methods are hindered by three significant bottlenecks: model mismatch error, sample average approximation error, and gradient approximation error. Model mismatch error stems from the misalignment between the model's parameterized predictive distribution and the true probability distribution. Sample average approximation error arises when using finite samples to approximate the expected optimization objective. Gradient approximation error occurs as DFL relies on the KKT condition for exact gradient computation, while most methods approximate the gradient for backpropagation in non-convex objectives. In this paper, we present DF2 -- the first \textit{distribution-free} decision-focused learning method explicitly designed to address these three bottlenecks. Rather than depending on a task-specific forecaster that requires precise model assumptions, our method directly learns the expected optimization function during training. To efficiently learn the function in a data-driven manner, we devise an attention-based model architecture inspired by the distribution-based parameterization of the expected objective. Our method is, to the best of our knowledge, the first to address all three bottlenecks within a single model. We evaluate DF2 on a synthetic problem, a wind power bidding problem, and a non-convex vaccine distribution problem, demonstrating the effectiveness of DF2.
