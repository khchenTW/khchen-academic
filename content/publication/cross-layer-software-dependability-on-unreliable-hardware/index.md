---
title: Cross-layer software dependability on unreliable hardware
publication_types:
  - "2"
authors:
  - Semeen Rehman
  - Kuan-Hsun Chen
  - Florian Kriebel
  - Anas Toma
  - Muhammad Shafique
  - Jian-Jia Chen
  - Jörg Henkel
doi: 10.1109/TC.2015.2417554
publication: IEEE Transactions on Computers
publication_short: IEEE Transactions on Computers
abstract: To enable reliable embedded systems, it is imperative to leverage the
  compiler and system software for joint optimization of functional correctness
  (i.e., vulnerability indexes) and timing correctness (i.e., deadline misses).
  This paper considers the optimization of the reliability-timing (RT) penalty,
  defined as a linear combination of the vulnerability and deadline misses. We
  propose a cross-layer approach to achieve reliable code generation and
  execution at compilation and system software layers for embedded systems. This
  is enabled by the concept of generating multiple versions for given
  application functions, with diverse performance and reliability tradeoffs, by
  exploiting different reliability-guided compilation options. As the execution
  time of a function is not fixed, the selection of the versions depends upon
  the execution behavior of the previous functions. Based on the reliability and
  execution time profiling of these versions, our reliability-driven system
  software decides the prioritization of the functions for determining their
  execution order and employs dynamic version selection to dynamically select a
  suitable version of a function. Specifically, our scheme builds a schedule
  table offline to optimize the RT penalty, and uses this table at run time to
  select suitable versions for the subsequent functions. A complex real-world
  application of “secure video and audio processing” composed of various
  functions is evaluated for reliable code generation and execution.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2015-03-27T17:23:53.268Z
---
