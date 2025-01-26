---
title: "TreeHouse: An MLIR-based Compilation Flow for Real-Time Tree-based Inference"
publication_types:
  - "2"
authors:
  - ChiaHui Su
  - Chia-Hua Ku
  - Jenq Kuen Lee
  - Kuan-Hsun Chen
doi: 10.1145/3704727
abstract: "Tree-based ensembles stand as the prominent resource-efficient
  approaches for real-time inference. To optimize their performance, researchers
  have developed several solutions to accommodate their unique program
  structure, i.e., consecutive branches and eliminate the floating-point
  arithmetic operations, which are usually costly at the embedded computing
  systems. Most of them are realized at the level of source code and a standard
  compilation is applied subsequently. Therefore, an end-to-end compilation flow
  may consolidate these methods and provide a holistic optimization. In this
  work, we introduce TreeHouse, a compilation flow based on MLIR designed for
  real-time inference of tree ensembles. First, we optimize the layout of basic
  blocks to reduce the expected branches during inference. Moreover, we provide
  a solution to facilitate LLVM register allocation for further efficiency. In
  addressing the suboptimal performance of floating-point operations in edge
  systems, we incorporate methods to convert data into integer format. We
  implemented and evaluated TreeHouse using two tree-based ensembles: boosting
  trees and random forests. Overall, boosting trees exhibited performance gains
  ranging from 1.38 × to 8.24 × on x86, 1.70 × to 6.61 × on ARMv8, and 1.75 × to
  4.52 × on RISC-V compared to state-of-the-art decision tree research. Random
  forests achieved performance gains of up to 1.6 × on x86, 2.03 × on ARMv8, and
  2.9 × on RISC-V."
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-01-26T18:06:06.295Z
---
