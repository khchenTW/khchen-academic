---
title: Efficiently approximating the probability of deadline misses in real-time
  systems
publication_types:
  - "1"
authors:
  - Georg von der Brüggen
  - Nico Piatkowski
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Katharina Morik
doi: 10.4230/LIPIcs.ECRTS.2018.6
publication: 30th Euromicro Conference on Real-Time Systems (ECRTS 2018)
publication_short: 30th Euromicro Conference on Real-Time Systems (ECRTS 2018)
abstract: This paper explores the probability of deadline misses for a set of
  constrained-deadline sporadic soft real-time tasks on uniprocessor platforms.
  We explore two directions to evaluate the probability whether a job of the
  task under analysis can finish its execution at (or before) a testing time
  point t. One approach is based on analytical upper bounds that can be
  efficiently computed in polynomial time at the price of precision loss for
  each testing point, derived from the well-known Hoeffding's inequality and the
  well-known Bernstein's inequality. Another approach convolutes the probability
  efficiently over multinomial distributions, exploiting a series of state space
  reduction techniques, i.e., pruning without any loss of precision, and
  approximations via unifying equivalent classes with a bounded loss of
  precision. We demonstrate the effectiveness of our approaches in a series of
  evaluations. Distinct from the convolution-based methods in the literature,
  which suffer from the high computation demand and are applicable only to task
  sets with a few tasks, our approaches can scale reasonably without losing much
  precision in terms of the derived probability of deadline misses.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2018-06-22T10:51:48.187Z
---
