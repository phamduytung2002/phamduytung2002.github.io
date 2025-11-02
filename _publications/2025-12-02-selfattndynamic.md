---
title: "Dynamical Properties of Tokens in Self-Attention and Effects of Positional Encoding"
permalink: /publication/2025-12-02-selfattndynamic
excerpt: '<strong>Duy-Tung Pham</strong>&#42;, An Nguyen The&#42;, Viet-Hoang Tran, Nhan-Phu Chung, Xin T. Tong, Tan Minh Nguyen&#42&#42, Thieu Vo&#42&#42'
# <br><br> TL;DR: We analyze the flow of tokens across attention layers and use these insights to enhance performance of Transformers.'
date: 2025-11-10
venue: 'The Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)'
# paperurl: 
bibtexurl: '/files/7_selfattndynamic.bib'
---
This paper investigates the dynamical properties of tokens in pre-trained Transformer models and explores their application to improving Transformers. To this end, we analyze the dynamical system governing the continuous-time limit of the pre-trained model and characterize the asymptotic behavior of its solutions. Specifically, we characterize when tokens move closer to or farther from one another over time, depending on the model parameters. We provide sufficient conditions, based on these parameters, to identify scenarios where tokens either converge to zero or diverge to infinity. Unlike prior works, our conditions are broader in scope and more applicable to real-world models. Furthermore, we investigate how different forms of positional encoding -- specifically absolute and rotary -- affect these dynamical regimes. Empirical evidence reveals that the convergence scenario adversely impacts model performance. Motivated by these insights, we propose simple refinements to Transformer architectures that mitigate convergence behavior in models with absolute or rotary positional encoding. These findings support theoretical foundations and design principles for improving Transformer models.
