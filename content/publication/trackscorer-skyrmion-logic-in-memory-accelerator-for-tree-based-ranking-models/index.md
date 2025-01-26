---
title: "TrackScorer: Skyrmion Logic-in-Memory Accelerator for Tree-based Ranking
  Models"
publication_types:
  - "1"
authors:
  - Elijah Seth Cishugi
  - Sebastian Buschjäger
  - Martijn Noorlander
  - Marco Ottavi
  - Kuan-Hsun Chen
publication: ACM/IEEE Design, Automation & Test in Europe Conference & Exhibition
publication_short: DATE 2025
abstract: >-
  Racetrack memories (RTMs) have been shown to have lower leakage power and
  higher density compared to

  traditional DRAM/SRAM technologies. However, their efficiency is often hindered by the need to shift the targeted data to access ports for read and write operations. Suitable mapping approaches are therefore essential to unleash their potential. In this work, we explore the mapping of the popular tree-based document ranking algorithm, Quickscorer, onto Skyrmion-based racetrack memories (SK-RTMs). Our approach leverages a Logic-in-Memory (LiM) accelerator, specifically designed to execute simple logic operations directly within SK-RTMs, enabling an efficient mapping of Quickscorer by exploiting its bitvector representation and inter-leaved traversal scheme of tree structures through bitwise logical operations. We present several mapping strategies, including one based on a quadratic assignment problem (QAP) optimization algorithm for optimal data placement of Quickscorer onto the racetracks. Our results demonstrate a significant reduction in read and write operations and, in certain cases, a decrease in the time spent shifting data during Quickscorer inference.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-01-26T18:28:40.962Z
---
