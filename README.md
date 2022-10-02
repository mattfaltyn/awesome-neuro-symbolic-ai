# Awesome Neuro-Symbolic AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Neuro-Symbolic AI (NSAI) frameworks, libraries, software, papers, and videos.

If you want to contribute to this list (please do), send me a pull request or contact me [@mattfaltyn](https://mattfaltyn.github.io/).

## Table of Contents
- [NSAI Classification](#nsai-classification)
- [Frameworks](#frameworks)

## NSAI Classification
Based on [Henry Kautz’s](https://en.wikipedia.org/wiki/Henry_Kautz) taxonomy of neuro-symbolic architectures from his Robert S. Englemore Memorial Lecture in 2020 at the Thirty-Fourth AAAI Conference on Artificial Intelligence. Images are taken directly from the [summary paper](https://onlinelibrary.wiley.com/doi/full/10.1002/aaai.12036) of his presentation. Class descriptions are synthesized using Kautz's presentation as well as Garcez et al's [Neurosymbolic AI: The 3rd Wave](https://arxiv.org/pdf/2012.05876.pdf). 

### 1. Type I: Symbolic Neural symbolic
Type I is standard deep learning. This class is included in the taxonomy as the input and output of a neural network can be symbols (such as words in language translation) that are vectorized within the model. Some Type I frameworks include:
- BERT
- RoBERTa
- GPT-3

### 2. Type II: Symbolic[Neural]
This is an over all symbolic solver which uses Neural model internally as subroutine for one or more function. Some examples include:
- AlphaGo


### 3. Type III: Neural:Symbolic
This is a more refined integration of Neural and Symbolic approaches where the Neural and Symbolic systems are leveraged for different tasks in a big pipeline. Both systems communicate with each other either to extract information or to improve the individual/collective systems performance. Some examples include:
- Neural-Concept Learner

### 4. Type IV: Neural:Symbolic → Neural
This type is categorized as Neuro-Symbolic systems where the symbolic knowledge is compiled into the structure of Neural models. Some examples include:
- Tree LSTMs

### 5. Type V: Neural_{Symbolic}
This category covers all the approached where the first-order logic language is tensorized and neural methods are used to perform reasoning over this tensorized first-order logic representation. Some examples include:
- [2020 - Logical Neural Networks](#logical-neural-network)
- [2020 - Logic Tensor Networks](#logic-tensor-networks)
- [2019 - Neural Logic Machines](#neural-logic-machines)
- 2017 - Hinge-Loss Markov Random Fields and Probabilistic Soft Logic
- 2016 - TensorLog
- 2006 - Markov Logic Networks

### 6. Type VI: Neuro[Symbolic]
Here, the overall Neural model performs symbolic reasoning by either learning the relations between the symbols or paying attention to selected symbols at certain point. 
- Graph Neural Networks





## Frameworks 


### Logical Neural Network
A `Neural = Symbolic` framework for sound and complete weighted real-value logic created by IBM Research. 

#### Software
- See the [IBM NSAI Toolkit](https://ibm.github.io/neuro-symbolic-ai/toolkit) for a full list of associated repositories. 

#### Media

##### Academic Papers
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

##### Blogs
- [2021 - IBM, MIT and Harvard release “Common Sense AI” dataset at ICML 2021](https://research.ibm.com/blog/icml-darpa-agent)
- [2021 - AI, you have a lot of explaining to do](https://research.ibm.com/blog/explaining-commonsense-ai)
- [2020 - NSQA: Neuro-Symbolic Question Answering](https://towardsdatascience.com/nsqa-neuro-symbolic-question-answering-6d14d98e88f3)
- [2020 - Getting AI to Reason: Using Logical Neural Networks for Knowledge-Based Question Answering](https://medium.com/swlh/getting-ai-to-reason-using-logical-neural-networks-for-knowledge-based-question-answering-60456654f5fa)
- [2020 - Neurosymbolic AI to Give Us Machines With True Common Sense](https://medium.com/swlh/neurosymbolic-ai-to-give-us-machines-with-true-common-sense-9c133b78ab13)




### Logic Tensor Networks
Sony's Logic Tensor Networks (LTN) is a neurosymbolic framework that supports querying, learning, and reasoning with both rich data and abstract knowledge about the world. LTN introduces a fully differentiable logical language, called Real Logic, whereby the elements of a first-order logic signature are grounded onto data using neural computational graphs and first-order fuzzy logic semantics.




### Neural Logic Machines
Google's Neural Logic Machine (NLM) is a neural-symbolic architecture for both inductive learning and logic reasoning. NLMs use tensors to represent logic predicates.



### Hinge-Loss Markov Random Fields and Probabilistic Soft Logic 
Bach et al's Hinge-Loss Markov Random Fields (HL-MRFs) are a new kind of probabilistic graphical model that generalizes different approaches to convex inference. We unite three approaches from the randomized algorithms, probabilistic graphical models, and fuzzy logic communities, showing that all three lead to the same inference objective. We then define HL-MRFs by generalizing this unified objective. The second new formalism, probabilistic soft logic (PSL), is a probabilistic programming language that makes HL-MRFs easy to define using a syntax based on first-order logic.



### TensorLog
Cohen's TensorLog is a probabilistic deductive database in which reasoning uses a differentiable process. In TensorLog, each clause in a logical theory is first converted into certain type of factor graph. Then, for each type of query to the factor graph, the message-passing steps required to perform belief propagation (BP) are “unrolled” into a function, which is differentiable.


### Markov Logic Networks
Matthew Richardson's and Pedro Domingos' Markov Logic Networks (MLNs) are a first-order knowledge base with a weight attached to each formula (or clause). Together with a set of constants representing objects in the domain, it specifies a ground Markov network containing one feature for each possible grounding of a first-order formula in the KB, with the corresponding weight.
