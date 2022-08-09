---
title: "BLOwing Trees to the Ground: Layout Optimization of Decision Trees on
  Racetrack Memory"
publication_types:
  - "1"
authors:
  - Christian Hakert
  - Asif-Ali Khan
  - Kuan-Hsun Chen
  - Fazal Hameed
  - Jeronimo Castrillon
  - Jian-Jia Chen
doi: 10.1109/DAC18074.2021.9586167
publication: 58th ACM/IEEE Design Automation Conference (DAC)
publication_short: 58th ACM/IEEE Design Automation Conference (DAC)
abstract: Modern distributed low power systems tend to integrate machine
  learning algorithms, which are directly executed on the distributed devices
  (on the edge). In resource constrained setups (e.g. battery driven sensor
  nodes), the execution of the machine learning models has to be optimized for
  execution time and energy consumption. Racetrack memory (RTM), an emerging
  non-volatile memory (NVM), promises to achieve these goals by offering
  unprecedented integration density, smaller access-latency and reduced energy
  consumption. However, in order to access data in RTM, it needs to be shifted
  to the access port first, resulting in latency and energy penalties. In this
  paper, we propose B.L.O. (Bidirectional Linear Ordering), a novel
  domain-specific approach for placing decision trees in RTMs. We reduce the
  total amount of shifts during inference by exploiting the tree structure and
  estimated access probabilities. We further apply the state-of-the-art methods
  to place data structures in RTM, without exploiting any domain-specific
  knowledge, to the decision trees and compare them to B. L.O. We formally prove
  that the B.L.O. solution has an approximation ratio of 4, i.e., its number of
  shifts is guaranteed to be at most 4 times the optimal number of shifts for a
  given decision tree. Throughout the experimental evaluation, we show that for
  the realistic use case B.L.O. empirically outperforms the state-of-the-art
  data placement method on average by 54.7% in terms of shifts, 19.2% in terms
  of runtime and 19.2% in terms of energy consumption.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-12-05T10:09:47.367Z
---
