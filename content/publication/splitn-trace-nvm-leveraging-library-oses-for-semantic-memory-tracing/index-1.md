---
title: "Split'n Trace NVM: Leveraging Library OSes for Semantic Memory Tracing"
publication_types:
  - "1"
authors:
  - Christian Hakert
  - Kuan-Hsun Chen
  - Simon Kuenzer
  - Sharan Santhanam
  - Shuo-Han Chen
  - Yuan-Hao Chang
  - Felipe Huici
  - Jian-Jia Chen
doi: 10.1109/NVMSA51238.2020.9188136
publication: 9th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
publication_short: 9th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
abstract: With the rise of non-volatile memory (NVM) as a replacement for
  traditional main memories (e.g. DRAM), memory access analysis is becoming an
  increasingly important topic. NVMs suffer from technical shortcomings as such
  as reduced cell endurance which call for precise memory access analysis in
  order to design maintenance strategies that can extend the memory's lifetime.
  While existing memory access analyzers trace memory accesses at various
  levels, from the application level with code instrumentation, down to the
  hardware level where software is executed on special analysis hardware, they
  usually interpret main memory as a consecutive area, without investigating the
  application semantics of different memory regions. In contrast, this paper
  presents a memory access simulator, which splits the main memory into semantic
  regions and enriches the simulation result with semantics from the analyzed
  application. We leverage a library-based operating system called Unikraft by
  ascribing memory regions of the simulation to the relevant OS libraries. This
  novel approach allows us to derive a detailed analysis of which libraries (and
  thus functionalities) are responsible for which memory access patterns.
  Through offline profiling with our simulator, we provide a fine-granularity
  analysis of memory access patterns that provide insights for the design of
  efficient NVM maintenance strategies.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-08-19T15:23:02.178Z
---
