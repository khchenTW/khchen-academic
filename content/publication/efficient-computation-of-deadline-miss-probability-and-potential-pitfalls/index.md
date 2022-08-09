---
title: Efficient computation of deadline-miss probability and potential pitfalls
publication_types:
  - "1"
authors:
  - Kuan-Hsun Chen
  - Niklas Ueter
  - Georg von der Brüggen
  - Jian-Jia Chen
doi: 10.23919/DATE.2019.8714908
publication: Design, Automation & Test in Europe Conference & Exhibition (DATE)
publication_short: Design, Automation & Test in Europe Conference & Exhibition (DATE)
abstract: In soft real-time systems, applications can tolerate rare deadline
  misses. Therefore, probabilistic arguments and analyses are applicable in the
  timing analyses for this class of systems, as demonstrated in many existing
  researches. Convolution-based analyses allow to derive tight deadline-miss
  probabilities, but suffer from a high time complexity. Among the analytical
  approaches, which result in a significantly faster runtime than the
  convolution-based approaches, the Chernoff bounds provide the tightest
  results. In this paper, we show that calculating the deadline-miss probability
  using Chernoff bounds can be solved by considering an equivalent convex
  optimization problem. This allows us to, on the one hand, decrease the runtime
  of the Chernoff bounds while, on the other hand, ensure a tighter
  approximation since a larger variable space can be searched more efficiently,
  i.e., by using binary search techniques over a larger area instead of a
  sequential search over a smaller area. We evaluate this approach considering
  synthesized task sets. Our approach is shown to be computationally efficient
  for large task systems, whilst experimentally suggesting reasonable
  approximation quality compared to an exact analysis.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2019-03-25T11:05:48.275Z
---
