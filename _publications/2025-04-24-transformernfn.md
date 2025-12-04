---
title: "Equivariant Neural Functional Networks for Transformers"
permalink: /publication/2025-04-24-transformernfn
excerpt: 'Viet-Hoang Tran&#42;, Thieu Vo&#42;, An Nguyen The&#42;, Tho Tran Huu, Minh-Khoi Nguyen-Nhat, Thanh Tran, <strong>Duy-Tung Pham</strong>, Tan Minh Nguyen'
# <br><br> TL;DR: This paper systematically studies neural functional networks (NFNs) for Transformers, presenting a design principle, and an equivariant NFN called Transformer-NFN, along with a benchmark dataset for evaluation.'
date: 2025-11-08
venue: 'The Thirteenth International Conference on Learning Representations (ICLR 2025)'
paperurl: 'https://openreview.net/forum?id=uBai0ukstY'
bibtexurl: '/files/4_transformernfn.bib'
codeurl: 'https://github.com/MathematicalAI-NUS/Transformer-NFN'
---
This paper systematically explores neural functional networks (NFN) for transformer architectures. NFN are specialized neural networks that treat the weights, gradients, or sparsity patterns of a deep neural network (DNN) as input data and have proven valuable for tasks like learnable optimizers, implicit data representations, and weight editing. While NFN have been extensively developed for MLP and CNN, no prior work has addressed their design for transformers, despite their importance in modern deep learning. This paper aims to address this gap by systematically studying NFN for transformers. We first determine the maximal symmetric group of the weights in a multi-head attention module and a necessary and sufficient condition under which two sets of hyperparameters of the module define the same function. We then define the weight space of transformer architectures and its associated group action, leading to design principles for NFN in transformers. Based on these, we introduce Transformer-NFN, an NFN equivariant under this group action. Additionally, we release a dataset of over 125,000 Transformers model checkpoints trained on two datasets with two tasks, providing a benchmark for evaluating Transformer-NFN and encouraging further research on transformer training and performance.
