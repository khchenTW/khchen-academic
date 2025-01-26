---
title: Racetrack Memory Optimized Linear Layout and Efficient Decomposition of
  Decision Trees
subtitle: ""
publication_types:
  - "2"
authors:
  - Christian Hakert
  - Asif-Ali Khan
  - Kuan-Hsun Chen
  - Fazal Hameed
  - Jeronimo Castrillon
  - Jian-Jia Chen
doi: 10.1109/TC.2022.3197094
publication: IEEE Transactions on Computers
publication_short: IEEE Transactions on Computers (TC)
abstract: "Modern low power distributed systems tend to integrate machine
  learning algorithms. In resource-constrained setups, the execution of the
  models has to be optimized for performance and energy consumption. Racetrack
  memory (RTM) promises to achieve these goals by offering unprecedented
  integration density, smaller access latency, and reduced energy consumption.
  However, to access data in RTM, it needs to be shifted to the access port
  first. We investigate decision trees and develop placement strategies to
  reduce the total number of shifts in RTM. "
draft: false
featured: false
tags:
  - Non-Volatile Memory
  - Decision Trees
  - Racetrack
image:
  filename: ""
  focal_point: Smart
  preview_only: false
summary: ""
date: 2022-08-08T09:26:54.094Z
---
Decision trees allow profiling during training, resulting in tree paths’ access probabilities. We map tree nodes to RTM so that the total number of shifts is minimal. Concretely, we present two different placement approaches: 1) where tree nodes are closely packed and placed uniformly in a single RTM location and 2) where decision tree nodes are decomposed to separate RTM blocks. We discuss theoretical cost models for both approaches, we formally prove an upper bound of 4× for the unified and an upper bound of 12× for the decomposed organization towards the optimal placement. We conduct a thorough experimental evaluation to compare our algorithms to the state-of-the-art placement strategies Our experimental evaluations show that the unified and decomposed solutions reduce the number of shifts by 58.1% and 80.1%, respectively, leading to a 53.8% and 46.3% reduction in the overall runtime and 52.6% and 61.7% reduction in the energy consumption, compared to a naive baseline.

<https://ieeexplore.ieee.org/document/9851943>