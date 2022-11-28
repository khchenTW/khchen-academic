---
title: "Formal Verification of Resource Synchronization Protocol
  Implementations: A Case Study in RTEMS"
subtitle: ""
publication_types:
  - "2"
  - "1"
authors:
  - Junjie Shi
  - Cordt von Egidy
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.1109/TCAD.2022.3197501
publication: Transactions on Computer-Aided Design of Integrated Circuits and
  Systems, presented in EMSOFT'22
publication_short: TCAD, presented in EMSOFT'22
abstract: "To avoid race conditions and ensure data integrity, resource
  synchronization protocols have been widely studied in real-time systems for
  decades, providing systematical policies to guarantee a bound on priority
  inversion-induced blocking time and the avoidance of deadlocks. However, the
  corresponding realization is often based on assumed abstractions and necessary
  adaptions in a real-time operating system, by which the theoretically proven
  properties of such a protocol may not be delivered, leading to potential
  mismatches. "
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-09T09:09:02.382Z
---
To prevent such mismatches, in this work, we propose to contract the obligations of involved primitives and operations and apply the deductive verification on a corresponding implementation. To this end, we present a modularized verification framework and demonstrate its applicability by verifying the official implementation of the Immediate Ceiling Priority Protocol (ICPP) and the Multiprocessor Resource Sharing Protocol (MrsP) in RTEMS, resulting in the discovery of long-stayed mismatches for both synchronization protocols. To resolve them, we provide a possible remedy for the ICPP and an additional precondition regarding nested locking for the MrsP.