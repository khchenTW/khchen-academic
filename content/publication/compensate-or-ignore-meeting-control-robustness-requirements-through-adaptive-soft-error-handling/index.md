---
title: Compensate or ignore? Meeting control robustness requirements through
  adaptive soft-error handling
subtitle: presented in LCTES'16
publication_types:
  - "2"
  - "1"
authors:
  - Kuan-Hsun Chen
  - Björn Bönninghoff
  - Jian-Jia Chen
  - Peter Marwedel
doi: 10.1145/2980930.2907952
publication: ACM SIGPLAN Notices
publication_short: ACM SIGPLAN Notices
abstract: To avoid catastrophic events like unrecoverable system failures on
  mobile and embedded systems caused by soft-errors, software-based error
  detection and compensation techniques have been proposed. Methods like
  error-correction codes or redundant execution can offer high flexibility and
  allow for application-specific fault-tolerance selection without the needs of
  special hardware supports. However, such software-based approaches may lead to
  system overload due to the execution time overhead. An adaptive deployment of
  such techniques to meet both application requirements and system constraints
  is desired. From our case study, we observe that a control task can tolerate
  limited errors with acceptable performance loss. Such tolerance can be modeled
  as a (m,k) constraint which requires at least m correct runs out of any k
  consecutive runs to be correct. In this paper, we discuss how a given (m,k)
  constraint can be satisfied by adopting patterns of task instances with
  individual error detection and compensation capabilities. We introduce static
  strategies and provide a formal feasibility analysis for validation.
  Furthermore, we develop an adaptive scheme that extends our initial approach
  with online awareness that increases efficiency while preserving analysis
  results. The effectiveness of our method is shown in a real-world case study
  as well as for synthesized task sets.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2016-06-13T16:20:48.422Z
---
