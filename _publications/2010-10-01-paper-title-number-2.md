---
title: "Average-Case Communication Complexity of Statistical Problems"
collection: publications
permalink: /publication/colt21
excerpt: ' '
date: 2021-07-03
authors: 'Cyrus Rashtchian*, David P. Woodruff*, Peng Ye*, <strong>Hanlin Zhu</strong>*'
venue: 'Conference on Learning Theory (COLT)'
paperurl: 'https://proceedings.mlr.press/v134/rashtchian21a.html'
arxivurl: 'https://arxiv.org/abs/2107.01335'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

[Download paper here](https://arxiv.org/pdf/2107.01335.pdf)

We study statistical problems, such as planted clique, its variants, and sparse principal component analysis in the context of average-case communication complexity. Our motivation is to understand the statistical-computational trade-offs in streaming, sketching, and query-based models. Communication complexity is the main tool for proving lower bounds in these models, yet many prior results do not hold in an average-case setting. We provide a general reduction method that preserves the input distribution for problems involving a random graph or matrix with planted structure. Then, we derive two-party and multi-party communication lower bounds for detecting or finding planted cliques, bipartite cliques, and related problems. As a consequence, we obtain new bounds on the query complexity in the edge-probe, vector-matrix-vector, matrix-vector, linear sketching, and $\mathbb{F}_2$-sketching models. Many of these results are nearly tight, and we use our techniques to provide simple proofs of some known lower bounds for the edge-probe model. 