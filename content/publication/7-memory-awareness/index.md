---
title: 7 Memory Awareness
publication_types:
  - "6"
authors:
  - Helena Kotthaus
  - Peter Marwedel
  - Mikail Yayla
  - Sebastian Buschjäger
  - Hussam Amrouch
  - Kuan-Hsun Chen
doi: 10.1515/9783110785944-007
publication: Volume 1 Machine Learning under Resource Constraints - Fundamentals
abstract: This section discusses optimization approaches for the efficient
  memory footprint reduction of machine learning algorithms that are written in
  the GNU R programming language. The presented optimization strategies target
  the memory management layer between the R interpreter and the operating system
  and reduce the memory overhead for large data structures by ensuring that
  memory will only be allocated for memory pages that are definitely required.
  The proposed approaches use additional information from the runtime
  environment, eg, the short-term usage pattern of a memory block, to guide
  optimization. The evaluation is based on statistical machine learning
  algorithms. When the memory consumption hits the point that the OS starts to
  swap out memory, optimization strategies are able to speed up computation by
  several orders of magnitude.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-11-30T13:41:05.820Z
---
