# Awesome Neuro-Symbolic AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Neuro-Symbolic AI (NSAI) frameworks, libraries, software, papers, and videos.

If you want to contribute to this list (please do), send me a pull request or contact me [@mattfaltyn](https://mattfaltyn.github.io/).

## NSAI Classification
Based on [Henry Kautz’s](https://en.wikipedia.org/wiki/Henry_Kautz) taxonomy of neuro-symbolic architectures. 

- **Symbolic Neural symbolic** — is the current approach of many neural models in natural language processing, where words or subword tokens are both the ultimate input and output of large language models. Examples include BERT, RoBERTa, and GPT-3.
- **Symbolic[Neural]** — is exemplified by AlphaGo, where symbolic techniques are used to call neural techniques. In this case the symbolic approach is Monte Carlo tree search and the neural techniques learn how to evaluate game positions.
- **Neural|Symbolic** — uses a neural architecture to interpret perceptual data as symbols and relationships that are then reasoned about symbolically. The Neural-Concept Learner is an example.
- **Neural:Symbolic → Neural** — relies on symbolic reasoning to generate or label training data that is subsequently learned by a deep learning model, e.g., to train a neural model for symbolic computation by using a Macsyma-like symbolic mathematics system to create or label examples.
- **Neural_{Symbolic}** — uses a neural net that is generated from symbolic rules. An example is the Neural Theorem Prover, which constructs a neural network from an AND-OR proof tree generated from knowledge base rules and terms. Logic Tensor Networks also fall into this category.
- **Neural[Symbolic]** — allows a neural model to directly call a symbolic reasoning engine, e.g., to perform an action or evaluate a state.

## Logic Tensor Networks (LTN) Framework


## Logical Neural Network (LNN) Framework
A `Neural = Symbolic` framework for sound and complete weighted real-value logic created by IBM Research. 


### Software
- See the [IBM NSAI Toolkit](https://ibm.github.io/neuro-symbolic-ai/toolkit) for a full list of associated repositories. 


### Papers

#### Academic
- [2022 - Foundations of Reasoning with Uncertainty via Real-valued Logics](https://arxiv.org/abs/2008.02429)
- [2022 - Extending Logical Neural Networks Using First-Order Theories](https://arxiv.org/pdf/2207.02978.pdf)
- [2021 - Neuro-Symbolic Inductive Logic Programming with Logical Neural Networks](https://arxiv.org/abs/2112.03324)
- [2021 - Training Logical Neural Networks by Primal–Dual Methods for Neuro-Symbolic Reasoning](https://ieeexplore.ieee.org/document/9415044)
- [2021 - Proof Extraction for Logical Neural Networks](https://openreview.net/forum?id=Xw3kb6UyA31) 
- [2021 - Neuro-Symbolic Approaches for Text-Based Policy Learning](https://aclanthology.org/2021.emnlp-main.245/)
- [2021 - Neuro-Symbolic Reinforcement Learning with First-Order Logic](https://aclanthology.org/2021.emnlp-main.283/)
- [2021 - LOA: Logical Optimal Actions for Text-based Interaction Games](https://aclanthology.org/2021.acl-demo.27/)
- [2021 - Reinforcement Learning with External Knowledge by using Logical Neural Networks](https://arxiv.org/abs/2103.02363)
- [2021 - LNN-EL: A Neuro-Symbolic Approach to Short-text Entity Linking](https://aclanthology.org/2021.acl-long.64/)
- [2021 - Leveraging Abstract Meaning Representation for Knowledge Base Question Answering](https://aclanthology.org/2021.findings-acl.339/)
- [2021 - Logic Embeddings for Complex Query Answering](https://arxiv.org/abs/2103.00418)
- [2020 - Logical Neural Networks](https://arxiv.org/abs/2006.13155)

#### Blogs
- [2021 - IBM, MIT and Harvard release “Common Sense AI” dataset at ICML 2021](https://research.ibm.com/blog/icml-darpa-agent)
- [2021 - AI, you have a lot of explaining to do](https://research.ibm.com/blog/explaining-commonsense-ai)
- [2020 - NSQA: Neuro-Symbolic Question Answering](https://towardsdatascience.com/nsqa-neuro-symbolic-question-answering-6d14d98e88f3)
- [2020 - Getting AI to Reason: Using Logical Neural Networks for Knowledge-Based Question Answering](https://medium.com/swlh/getting-ai-to-reason-using-logical-neural-networks-for-knowledge-based-question-answering-60456654f5fa)
- [2020 - Neurosymbolic AI to Give Us Machines With True Common Sense](https://medium.com/swlh/neurosymbolic-ai-to-give-us-machines-with-true-common-sense-9c133b78ab13)

## Neural Logic Machines (NLM) Framework
Google's Neural Logic Machine (NLM) is a neural-symbolic architecture for both inductive learning and logic reasoning. NLMs use tensors to represent logic predicates. 

