---
title: Bit Error Tolerance Metrics for Binarized Neural Networks
publication_types:
  - "1"
authors:
  - Sebastian Buschjäger
  - Jian-Jia Chen
  - Kuan-Hsun Chen
  - Mario Günzel
  - Katharina Morik
  - Rodion Novkin
  - Lukas Pfahler
  - Mikail Yayla
doi: 10.48550/arXiv.2102.01344
publication: arXiv preprint arXiv:2102.01344
publication_short: arXiv preprint arXiv:2102.01344
abstract: >-
  To reduce the resource demand of neural network (NN) inference systems, it has
  been proposed to use approximate memory, in which the supply voltage and the
  timing parameters are tuned trading accuracy with energy consumption and
  performance. Tuning these parameters aggressively leads to bit errors, which
  can be tolerated by NNs when bit flips are injected during training. However,
  bit flip training, which is the state of the art for achieving bit error
  tolerance, does not scale well; it leads to massive overheads and cannot be
  applied for high bit error rates (BERs). Alternative methods to achieve bit
  error tolerance in NNs are needed, but the underlying principles behind the
  bit error tolerance of NNs have not been reported yet. With this lack of
  understanding, further progress in the research on NN bit error tolerance will
  be restrained.

  In this study, our objective is to investigate the internal changes in the NNs that bit flip training causes, with a focus on binarized NNs (BNNs). To this end, we quantify the properties of bit error tolerant BNNs with two metrics. First, we propose a neuron-level bit error tolerance metric, which calculates the margin between the pre-activation values and batch normalization thresholds. Secondly, to capture the effects of bit error tolerance on the interplay of neurons, we propose an inter-neuron bit error tolerance metric, which measures the importance of each neuron and computes the variance over all importance values. Our experimental results support that these two metrics are strongly related to bit error tolerance.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-02-02T12:45:47.543Z
---
