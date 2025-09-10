---
title: Wedge-Parallel Triangle Counting for GPUs
publication_types:
  - "1"
authors:
  - Jeffrey Spaan
  - Kuan-Hsun Chen
  - David A. Bader
  - Ana Lucia Varbanescu
doi: 10.1007/978-3-031-99872-0_1
publication: European Conference on Parallel Processing
publication_short: Euro-Par 2025
abstract: For fast processing of increasingly large graphs, triangle counting –
  a common building block of graph processing algorithms, is often performed on
  GPUs. However, applying massive parallelism to triangle counting is
  challenging due to the algorithm’s inherent irregular access patterns and
  workload imbalance. In this work, we propose WeTriC, a novel wedge-parallel
  triangle counting algorithm for GPUs, which, using fine(r)-grained parallelism
  through a lightweight static mapping of wedges to threads, improves load
  balancing and efficiency. Our theoretical analysis compares different
  parallelization granularities, while optimizations enhance caching, reduce
  work-per-intersection, and minimize overhead. Performance experiments indicate
  that WeTriC yields 5.63x and speedup 4.69x over optimized vertex-parallel and
  edge-parallel binary search triangle counting algorithms, respectively.
  Furthermore, we show that WeTriC consistently outperforms the state-of-the-art
  (i.e., on avg. 2.86x faster than Trust and 2.32x faster than GroupTC).
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-09-10T19:34:12.788Z
---
