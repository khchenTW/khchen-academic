---
title: Margin-maximization in binarized neural networks for optimizing bit error
  tolerance
publication_types:
  - "1"
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
doi: 10.23919/DATE51398.2021.9473918
publication: Design, Automation & Test in Europe Conference & Exhibition (DATE)
publication_short: Design, Automation & Test in Europe Conference & Exhibition (DATE)
abstract: To overcome the memory wall in neural network (NN) inference systems,
  recent studies have proposed to use approximate memory, in which the supply
  voltage and access latency parameters are tuned, for lower energy consumption
  and faster access at the cost of reliability. To tolerate the occuring bit
  errors, the state-of-the-art approaches apply bit flip injections to the NNs
  during training, which require high overheads and do not scale well for large
  NNs and high bit error rates. In this work, we focus on binarized NNs (BNNs),
  whose simpler structure allows better exploration of bit error tolerance
  metrics based on margins. We provide formal proofs to quantify the maximum
  number of bit flips that can be tolerated. With the proposed margin-based
  metrics and the well-known hinge loss for maximum margin classification in
  support vector machines (SVMs), we are able to construct a modified hinge loss
  (MHL) to train BNNs for bit error tolerance without any bit flip injections.
  Our experimental results indicate that the MHL enables the possibility for
  BNNs to tolerate higher bit error rates than with bit flip training and,
  therefore, allows to further lower the requirements on approximate memories
  used for BNNs.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-02-01T10:19:20.220Z
---
