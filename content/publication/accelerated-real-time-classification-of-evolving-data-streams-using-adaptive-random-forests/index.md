---
title: Accelerated Real-Time Classification of Evolving Data Streams using
  Adaptive Random Forests
publication_types:
  - "1"
authors:
  - Frank Ridder
  - Kuan-Hsun Chen
  - Nikolaos Alachiotis
publication: International Conference on Field-Programmable Technology
publication_short: FPT
abstract: >-
  Machine learning is increasingly applied to a wide range of real-time
  applications, with classification tasks playing

  a critical role in enabling intelligent decision-making. However, the phenomenon of concept drift, where the underlying data distribution changes over time, presents a significant challenge to maintaining the accuracy of machine learning models in applications with evolving data streams such as health monitoring or sensor-data analyses. The Adaptive Random Forest (ARF) algorithm addresses this issue by coupling multiple Hoeffding

  Trees with a drift detector to adapt to concept drift. As training a forest of growing decision trees is a high-latency operation, custom-hardware acceleration is needed to meet the stringent latency requirements for real-time use of ARF. To the best of our knowledge, this work describes the first FPGA implementation of the ARF algorithm, focusing on achieving high hardware efficiency, scalability, and adaptability for four different datasets. We present a parameterized design that incorporates various levels of parallelism, resource sharing, and pipelining, delivering

  15x-79x faster execution than a 40-core CPU while losing a maximum of 13% accuracy. Furthermore, 3x-33x faster than a state-of-the-art GPU solution using an NVIDIA TESLA V100 while demonstrating accuracy scores within 0.3% to 15% of these GPU ARF implementations.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-11-15T11:20:52.429Z
---
