---
title: "Mixture of Experts - Simplified"
collection: talks
type: "Self Talks"
permalink: /talks/mixture-of-experts
venue: "SimpleSphere, Jalgaon"
date: 2014-11-17
location: "Maharashtra, Ind"
---

The size of a model plays a big role in improving its quality. If you have a set amount of computing power, it’s better to train a bigger model for a shorter time than a smaller model for a longer time.

**Mixture of Experts (MoE)** makes it possible to train models using much less computing power. This means you can make the model or the dataset much bigger without needing extra resources compared to a regular model. An MoE model can reach the same quality as a regular model much faster during training.

So, what exactly is a MoE? In the context of transformer models, a MoE consists of two main concepts:

**Sparse Mixture of Experts** : Instead of using regular dense layers, MoE layers use multiple “experts” (like 8 small neural networks). Each expert is usually a simple feed-forward network but can also be more complex or even another MoE.

**Token Routing** : A gate network (router) decides which expert handles each input token. For example, one word may go to Expert 1 while another goes to Expert 2. The router learns this during training and can also send a token to multiple experts if needed.
