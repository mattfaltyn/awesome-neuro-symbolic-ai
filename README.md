# Awesome Neuro-Symbolic AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Neuro-Symbolic AI (NSAI or NeSy) frameworks, libraries, software, papers, and videos.

If you want to contribute to this list (please do), send me a pull request or contact me [@mattfaltyn](https://mattfaltyn.github.io/).

## Table of Contents
- [NSAI Basics](#nsai-basics)
- [NSAI Classification](#nsai-classification)
- [Frameworks](#frameworks)

## NSAI Basics

### What is NSAI?
According to the [Sixteenth International Workshop on Neural-Symbolic Learning and Reasoning](https://sites.google.com/view/nesy-2022/) website, NSAI "aims to build rich computational AI models, systems and applications by combining neural and symbolic learning and reasoning. It hopes to create synergies among the strengths of neural and symbolic AI while overcoming their complementary weaknesses."

### NSAI Overview Articles
- [2022 - Towards Data-and Knowledge-Driven Artificial Intelligence: A Survey on Neuro-Symbolic Computing](https://arxiv.org/abs/2210.15889)
- [2022 - Is Neuro-Symbolic AI Meeting its Promise in Natural Language Processing? A Structured Review](https://arxiv.org/abs/2202.12205)
- [2021 - Neuro-Symbolic Artificial Intelligence: Current Trends](https://arxiv.org/abs/2105.05330)
- [2021 - Neuro-Symbolic VQA: A review from the perspective of AGI desiderata](https://arxiv.org/abs/2104.06365)
- [2017 - Neural-Symbolic Learning and Reasoning: A Survey and Interpretation](https://arxiv.org/abs/1711.03902)
- [2015 - Neural-Symbolic Learning and Reasoning: Contributions and Challenges](https://openaccess.city.ac.uk/id/eprint/11838/)
- [2009 - The Facets of Artificial Intelligence: A Framework to Track the Evolution of AI](https://www.ijcai.org/proceedings/2018/0718.pdf)
- [2005 - Dimensions of Neural-symbolic Integration - A Structured Survey](https://arxiv.org/abs/cs/0511042)
- [2004 - The Integration of Connectionism and First-Order Knowledge Representation and Reasoning as a Challenge for Artificial Intelligence](https://ui.adsabs.harvard.edu/abs/2004cs........8069B/abstract)

## NSAI Classification
Based on [Henry Kautz’s](https://en.wikipedia.org/wiki/Henry_Kautz) taxonomy of neuro-symbolic architectures from his Robert S. Englemore Memorial Lecture in 2020 at the Thirty-Fourth AAAI Conference on Artificial Intelligence. Images are taken directly from [Harsha Kokel's](https://harshakokel.com/) [Types of Neuro-Symbolic Systems
](https://harshakokel.com/posts/neurosymbolic-systems/) blog post. Class descriptions are synthesized using Kautz's presentation as well as Garcez et al's [Neurosymbolic AI: The 3rd Wave](https://arxiv.org/pdf/2012.05876.pdf). 

### Type I: Symbolic Neural symbolic
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-I.png" height="150">

A Type I system is standard deep learning. This class is included in the taxonomy as the input and output of a neural network can be symbols (such as words in language translation) that are vectorized within the model. Some Type I frameworks include:
- BERT
- RoBERTa
- GPT-3

### Type II: Symbolic[Neural]
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-II.png" height="150">

A Type II system is a hybrid system in which a symbolic solver utilizes neural networks as subroutines to solve one or more tasks. Some Type II frameworks include:
- AlphaGo


### Type III: Neural:Symbolic
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-III.png" height="200">

A Type III system is a hybrid system where a neural network solves one task and interacts via its input and output with a symbolic system that solves a different task. Some Type III frameworks include:
- Neural-Concept Learner

### Type IV: Neural:Symbolic → Neural
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-IV.png" height="200">

Type IV is a system in which the symbolic knowledge is compiled into the training set of a neural network. Some Type IV frameworks include:
- [2020 - Logical Neural Networks](#logical-neural-network)

### Type V: Neural_{Symbolic}
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-V.png" height="120">

A Type V system is a tightly-coupled but distributed neuralsymbolic systems where a symbolic logic rule is mapped onto an embedding which acts as a soft-constraint on the network’s loss function. These systems are often tensorized in some manner. Some Type V frameworks include:
- [2020 - Logic Tensor Networks](#logic-tensor-networks)
- [2019 - Neural Logic Machines](#neural-logic-machines)
- 2017 - Hinge-Loss Markov Random Fields and Probabilistic Soft Logic
- 2016 - TensorLog
- 2006 - Markov Logic Networks

### Type VI: Neuro[Symbolic]
<img src="https://github.com/traincheck-ai/awesome-neuro-symbolic-ai/blob/main/images/type-VI.png" height="150">

A Type VI system should be capable of true symbolic and combinatorial reasoning inside a neural engine. While no Type VI framework exists, here are some approaches: 
- Graph Neural Networks





## Frameworks 

In this section, we aim to provide the most comprehensive NSAI frameworks.

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
- [2020 - Logical Neural Networks](https://skirmilitor.medium.com/logical-neural-networks-31498d1aa9be)
- [2020 - NSQA: Neuro-Symbolic Question Answering](https://towardsdatascience.com/nsqa-neuro-symbolic-question-answering-6d14d98e88f3)
- [2020 - Semantic Parsing using Abstract Meaning Representation](https://medium.com/@sroukos/semantic-parsing-using-abstract-meaning-representation-95242518a380)
- [2020 - A Semantic Parsing-based Relation Linking approach for Knowledge Base Question Answering](https://medium.com/@sroukos/a-semantic-parsing-based-relation-linking-approach-for-knowledge-base-question-answering-93c14d7931c1)
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
