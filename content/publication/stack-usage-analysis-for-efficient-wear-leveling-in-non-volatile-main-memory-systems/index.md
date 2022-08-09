---
title: Stack Usage Analysis for Efficient Wear Leveling in Non-Volatile Main
  Memory Systems
publication_types:
  - "1"
  - "5"
authors:
  - Christian Hakert
  - Mikail Yayla
  - Kuan-Hsun Chen
  - Georg von der Brüggen
  - Jian-Jia Chen
  - Sebastian Buschjäger
  - Katharina Morik
  - Paul R Genssler
  - Lars Bauer
  - Hussam Amrouch
  - Jörg Henkel
doi: 10.1109/MLCAD48534.2019.9142113
publication: 9 ACM/IEEE 1st Workshop on Machine Learning for CAD (MLCAD)
publication_short: 9 ACM/IEEE 1st Workshop on Machine Learning for CAD (MLCAD)
abstract: Emerging non-volatile memory (NVM) technologies, such as Phase Change
  Memory (PCM), have been considered as a replacement for DRAM and storage due
  to their low power consumption, fast access speed, and low unit cost. Even so,
  some NVMs have a significantly lower write endurance and hence in-memory wear
  leveling is an important requirement for practical applicability. Since writes
  to the stack often target a small and dense memory region, generic,
  coarse-grained wear-leveling mechanisms (e.g. virtual memory page remapping)
  are not sufficient. An alternative solution is to relocate the stack memory
  regularly, which involves copying of the stack content. As the stack content
  changes in size during the execution of an application, the copy overhead can
  be significantly mitigated by performing the relocation when the stack size is
  small.In this paper, we investigate two approaches to determine points in time
  when the stack is small. First, we analyze the possibility to fit simple
  machine-learning models to the stack usage function. Precise predictions of
  this function enable the identification of the minimum stack size during
  execution. In our evaluation, the tested models provide accurate estimates of
  the future stack usage function for a subset of common applications.As a
  second approach, we analyze applications a priori and determine potential
  optimal points to perform relocation in the instruction stream. In detail, we
  deploy the application in an analysis environment, which determines a rating
  for each executed instruction. Based on this rating, we apply a genetic
  algorithm to identify the best points in the instruction stream to perform the
  stack relocation. This approach allows to save up to 85% of the write overhead
  for wear-leveling in our experiments
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2019-09-03T14:45:22.811Z
---
