---
title: Software-Managed Read and Write Wear-Leveling for Non-Volatile Main Memory
publication_types:
  - "2"
authors:
  - Christian Hakert
  - Kuan-Hsun Chen
  - Horst Schirmeier
  - Lars Bauer
  - Paul R. Genssler
  - Georg von der Brueggen
  - Hussam Amrouch
  - Joerg Henkel
  - Jian-Jia Chen
doi: 10.1145/3483839
publication: ACM Transactions on Embedded Computing Systems (TECS)
publication_short: ACM Trans. Embed. Comput. Syst. (TECS)
abstract: "In-memory wear-leveling has become an important research field for
  emerging non-volatile main memories over the past years. Many approaches in
  the literature perform wear-leveling by making use of special hardware. Since
  most non-volatile memories only wear out from write accesses, the proposed
  approaches in the literature also usually try to spread write accesses widely
  over the entire memory space. Some non-volatile memories, however, also wear
  out from read accesses, because every read causes a consecutive write access.
  Software-based solutions only operate from the application or kernel level,
  where read and write accesses are realized with different instructions and
  semantics. Therefore different mechanisms are required to handle reads and
  writes on the software level. "
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-02-10T10:42:31.048Z
---
First, we design a method to approximate read and write accesses to the memory to allow aging aware coarse-grained wear-leveling in the absence of special hardware, providing the age information. Second, we provide specific solutions to resolve access hot-spots within the compiled program code (text segment) and on the application stack. In our evaluation, we estimate the cell age by counting the total amount of accesses per cell. The results show that employing all our methods improves the memory lifetime by up to a factor of 955×.