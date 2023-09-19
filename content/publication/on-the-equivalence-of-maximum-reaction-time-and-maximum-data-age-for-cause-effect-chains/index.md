---
title: On the Equivalence of Maximum Reaction Time and Maximum Data Age for
  Cause-Effect Chains
subtitle: Best Paper Award in ECRTS'23
publication_types:
  - "1"
authors:
  - Mario Günzel
  - Kuan-Hsun Chen
  - Niklas Ueter
  - Jian-Jia Chen
doi: 10.4230/LIPIcs.ECRTS.2023.10
publication: 35th Euromicro Conference on Real-Time Systems (ECRTS 2023)
publication_short: ECRTS
abstract: >-
  Real-time systems require a formal guarantee of timing-constraints, not only
  for individual tasks but also for data-propagation. The timing behavior of
  data-propagation paths in a given system is typically described by its maximum
  reaction time and its maximum data age. This paper shows that they are
  equivalent.

  To reach this conclusion, partitioned job chains are introduced, which consist of one immediate forward and one immediate backward job chain. Such partitioned job chains are proven to describe maximum reaction time and maximum data age in a universal manner. This universal description does not only show the equivalence of maximum reaction time and maximum data age, but can also be exploited to speed up the computation of such significantly. In particular, the speed-up for synthesized task sets based on automotive benchmarks can be up to 1600.

  Since only very few non-restrictive assumptions are made, the equivalence of maximum data age and maximum reaction time holds for almost any scheduling mechanism and even for tasks which do not adhere to the typical periodic or sporadic task model. This observation is supported by a simulation of a ROS2 navigation system.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-09-19T18:59:57.003Z
---
