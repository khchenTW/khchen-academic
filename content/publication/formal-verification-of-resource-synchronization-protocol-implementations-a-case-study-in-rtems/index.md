---
title: "Formal Verification of Resource Synchronization Protocol
  Implementations: A Case Study in RTEMS"
subtitle: to be appeared in EMSOFT'22
publication_types:
  - "2"
  - "1"
authors:
  - Junjie Shi
  - Cordt von Egidy
  - Kuan-Hsun Chen
  - Jian-Jia Chen
publication: Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
publication_short: Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
abstract: "To avoid race conditions and ensure data integrity, resource
  synchronization protocols have been widely studied in real-time systems for
  decades, providing systematical policies to guarantee a bound on priority
  inversion-induced blocking time and the avoidance of deadlocks. However, the
  corresponding realization is often based on assumed abstractions and necessary
  adaptions in a real-time operating system, by which the theoretically proven
  properties of such a protocol may not be delivered, leading to potential
  mismatches. "
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-08T09:09:02.382Z
---
To prevent such mismatches, in this work, we propose to contract the obligations of involved primitives and operations and apply the deductive verification on a corresponding implementation. To this end, we present a modularized verification framework and demonstrate its applicability by verifying the official implementation of the Immediate Ceiling Priority Protocol (ICPP) and the Multiprocessor Resource Sharing Protocol (MrsP) in RTEMS, resulting in the discovery of long-stayed mismatches for both synchronization protocols. To resolve them, we provide a possible remedy for the ICPP and an additional precondition regarding nested locking for the MrsP.