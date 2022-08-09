---
title: "Ns-ftl: Alleviating the uneven bit-level wearing of nvram-based ftl via
  nand-spin"
publication_types:
  - "1"
authors:
  - Wei-Chun Cheng
  - Shuo-Han Chen
  - Yuan-Hao Chang
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Tseng-Yi Chen
  - Ming-Chang Yang
  - Wei-Kuan Shih
doi: 10.1109/NVMSA51238.2020.9188172
publication: 9th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
publication_short: 9th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
abstract: Non-Volatile random access memory (NVRAM) has been regarded as a
  promising DRAM alternative with its nonvolatility, near-zero idle power
  consumption, and byte addressability. In particular, some NVRAM devices, such
  as Spin Torque Transfer (STT) RAM, can provide the same or better access
  performance and lower power consumption when compared with dynamic random
  access memory (DRAM). These nice features make NVRAM become an attractive DRAM
  replacement on NAND flash storage for resolving the management overhead of the
  flash translation layer (FTL). For instance, when adopting NVRAM for storing
  the mapping entries of FTL, the overheads of loading and storing the mapping
  entries between the non-volatile NAND flash and the volatile DRAM can be
  eliminated. Nevertheless, due to the limited lifetime constraint of NVRAM, the
  bit-level update behavior of FTL may lead to the issue of uneven bit-level
  wearing and the lifetime capacity of those less-worn NVRAM cells could be
  underutilized. Such an observation motivates this study to utilize the
  emerging NAND-like Spin Torque Transfer memory (NAND-SPIN) for alleviating the
  uneven bit-level wearing of NVRAM-based FTL and making the best of the
  lifetime capacity of each NAND-SPIN cell. The experimental results show that
  the proposed design can effectively avoid the uneven bit-level wearing, when
  compared with page-based FTL on NAND-SPIN.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-08-19T14:10:29.479Z
---
