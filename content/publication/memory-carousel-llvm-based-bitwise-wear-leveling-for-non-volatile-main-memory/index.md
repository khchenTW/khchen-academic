---
title: "Memory Carousel: LLVM-Based Bitwise Wear-Leveling for Non-Volatile Main
  Memory"
subtitle: Just accepted
publication_types:
  - "2"
authors:
  - Nils Hölscher
  - Christian Hakert
  - Hassan Nassar
  - Kuan-Hsun Chen
  - Lars Bauer
  - Jian-Jia Chen
  - Jörg Henkel
publication: IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems
publication_short: TCAD
abstract: Emerging non-volatile memory yields, alongside many advantages,
  technical shortcomings, such as reduced cell lifetime. Although many
  wear-leveling approaches exist to extend the lifetime of such memories,
  usually a trade-off for the granularity of wear-leveling has to be made. Due
  to iterative write schemes (repeatedly sense and write), wear-out of memory in
  certain systems is directly dependant on the written bit value and thus can be
  highly imbalanced, requiring dedicated bit-wise wear-leveling. Such a bit-wise
  wear-leveling so far has only been proposed together with a special hardware
  support. However, if no dedicated hardware solutions are available, especially
  for commercial off-the-shelf systems with non-volatile memories, a software
  solution can be crucial for the system lifetime. In this work, we propose
  entirely software-based bit-wise wear leveling, where the position of bits
  within CPU words in main memory is rotated on a regular basis. We leverage the
  LLVM intermediate representation to adjust load and store operations of the
  application with a custom compiler pass. Experimental evaluation shows that
  the lifetime by applying local rotation within the CPU word can be extended by
  a factor of up to 21×. We also show that our method can incorporate with
  coarser-grained wear-leveling, e.g. on block granularity and assist
  achievement of higher lifetime improvements.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-11-29T11:12:25.542Z
---
