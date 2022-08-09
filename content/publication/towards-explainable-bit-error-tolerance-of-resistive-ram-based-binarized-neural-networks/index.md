---
title: Towards explainable bit error tolerance of resistive ram-based binarized
  neural networks
publication_types:
  - "2"
authors:
  - Sebastian Buschjäger
  - Jian-Jia Chen
  - Kuan-Hsun Chen
  - Mario Günzel
  - Christian Hakert
  - Katharina Morik
  - Rodion Novkin
  - Lukas Pfahler
  - Mikail Yayla
doi: 10.48550/arXiv.2002.00909
publication: arXiv preprint arXiv:2002.00909
publication_short: arXiv preprint arXiv:2002.00909
abstract: "Non-volatile memory, such as resistive RAM (RRAM), is an emerging
  energy-efficient storage, especially for low-power machine learning models on
  the edge. It is reported, however, that the bit error rate of RRAMs can be up
  to 3.3% in the ultra low-power setting, which might be crucial for many use
  cases. Binary neural networks (BNNs), a resource efficient variant of neural
  networks (NNs), can tolerate a certain percentage of errors without a loss in
  accuracy and demand lower resources in computation and storage. The bit error
  tolerance (BET) in BNNs can be achieved by flipping the weight signs during
  training, as proposed by Hirtzlin et al., but their method has a significant
  drawback, especially for fully connected neural networks (FCNN): The FCNNs
  overfit to the error rate used in training, which leads to low accuracy under
  lower error rates. In addition, the underlying principles of BET are not
  investigated. In this work, we improve the training for BET of BNNs and aim to
  explain this property. We propose straight-through gradient approximation to
  improve the weight-sign-flip training, by which BNNs adapt less to the bit
  error rates. To explain the achieved robustness, we define a metric that aims
  to measure BET without fault injection. We evaluate the metric and find that
  it correlates with accuracy over error rate for all FCNNs tested. Finally, we
  explore the influence of a novel regularizer that optimizes with respect to
  this metric, with the aim of providing a configurable trade-off in accuracy
  and BET."
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-02-03T15:02:43.754Z
---
