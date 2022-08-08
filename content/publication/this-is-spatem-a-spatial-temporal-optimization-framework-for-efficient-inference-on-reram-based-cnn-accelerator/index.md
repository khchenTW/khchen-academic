---
title: This is SPATEM! A Spatial-Temporal Optimization Framework for Efficient
  Inference on ReRAM-based CNN Accelerator
publication_types:
  - "1"
authors:
  - Yen-Ting Tsou
  - Kuan-Hsun Chen
  - Chia-Lin Yang
  - Hsiang-Yun Cheng
  - Jian-Jia Chen
  - Der-Yu Tsai
author_notes: []
doi: 10.1109/ASP-DAC52403.2022.9712536
publication: " 27th Asia and South Pacific Design Automation Conference (ASP-DAC)"
publication_short: " 27th Asia and South Pacific Design Automation Conference (ASP-DAC)"
abstract: Resistive memory-based computing-in-memory (CIM) has been considered
  as a promising solution to accelerate convolutional neural networks (CNN)
  inference, which stores the weights in crossbar memory arrays and performs
  in-situ matrix-vector multiplications (MVMs) in an analog manner. Several
  techniques assume that a whole crossbar can operate concurrently and discuss
  how to efficiently map the weights onto crossbar arrays. However, in practice,
  the accumulated effect of per-cell current deviation and
  Analog-to-Digital-Converter overhead may greatly degrade inference accuracy,
  which motivates the concept of Operation Unit (OU), by which an operation per
  cycle in a crossbar only involve limited wordlines and bitlines to preserve
  satisfactory inference accuracy. With OU-based operations, the mapping of
  weights and scheduling strategy for parallelizing CNN convolution operations
  should take the cost of communication overhead and resource utilization into
  consideration to optimize the inference acceleration. In this work, we propose
  the first optimization framework named SPATEM, that efficiently executes MVMs
  with OU-based operations on ReRAM-based CIM accelerators. It decouples the
  design space into tractable steps, models the expected inference latency, and
  derives an optimized spatial-temporal-aware scheduling strategy. By comparing
  with state-of-the-arts, the experimental result shows that the derived
  scheduling strategy of SPATEM achieves on average 29.24% inference latency
  reduction with 31.28% less communication overhead by exploiting more
  originally unused crossbar cells.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-08T13:31:33.884Z
---
