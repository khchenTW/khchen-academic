---
title: Using a set of triangle inequalities to accelerate k-means clustering
publication_types:
  - "1"
authors:
  - Qiao Yu
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.1007/978-3-030-60936-8_23
publication: International Conference on Similarity Search and Applications
publication_short: International Conference on Similarity Search and Applications
abstract: The k-means clustering is a well-known problem in data mining and
  machine learning. However, the de facto standard, i.e., Lloyd’s k-mean
  algorithm, suffers from a large amount of time on the distance calculations.
  Elkan’s k-means algorithm as one prominent approach exploits triangle
  inequality to greatly reduce such distance calculations between points and
  centers, while achieving the exactly same clustering results with significant
  speed improvement, especially on high-dimensional datasets. In this paper, we
  propose a set of triangle inequalities to enhance the filtering step of
  Elkan’s k-means algorithm. With our new filtering bounds, a filtering-based
  Elkan (FB-Elkan) is proposed, which preserves the same results as Lloyd’s
  k-means algorithm and additionally prunes unnecessary distance calculations.
  In addition, a memory-optimized Elkan (MO-Elkan) is provided, where the space
  complexity is greatly reduced by trading-off the maintenance of lower bounds
  and the run-time efficiency. Throughout evaluations with real-world datasets,
  FB-Elkan in general accelerates the original Elkan’s k-means algorithm for
  high-dimensional datasets (up to 1.69x), whereas MO-Elkan outperforms the
  others for low-dimensional datasets (up to 2.48x). Specifically, when the
  datasets have a large number of points, i.e., n≥5M, MO-Elkan still can derive
  the exact clustering results, while the original Elkan’s k-means algorithm is
  not applicable due to memory limitation.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-10-14T14:08:05.706Z
---
