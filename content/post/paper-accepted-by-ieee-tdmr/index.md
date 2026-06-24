---
title: Paper Accepted by IEEE TDMR
date: 2026-06-24T09:30:55.533Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
I am happy to share that our paper, “Instruction Error Detection with Bloom Filters: Architecture, Radiation Testing and Fault Injection,” has been accepted by IEEE Transactions on Device and Materials Reliability.

Congratulations to Elijah Seth Cishugi, who led this work as part of his PhD research. Elijah is supervised by Marco Ottavi, and I am glad to support his PhD as co-supervisor. The paper is also a nice joint effort with Tijmen T. Smit, Bruno Forlin, and Carlo Cazzaniga.

The work studies how Bloom filters can be used as a lightweight, probabilistic checker for detecting instruction-memory errors. Instead of relying only on conventional ECC-based protection, the proposed checker stores valid instruction/address pairs and detects corrupted instruction fetches through membership queries. This is particularly interesting for systems exposed to radiation-induced soft errors, where multi-bit upsets may become increasingly relevant.

A key part of the paper is the experimental validation. The checker was evaluated through emulation-based fault injection and two neutron-beam irradiation campaigns. The results show that the Bloom-filter-based checker can maintain detection rates close to the theoretical target, including cases where multi-bit errors make ECC diagnosis less reliable. The paper further integrates the checker into the instruction-fetch path of a NEORV32 RISC-V soft core, showing its practical applicability in a processor setting with static instruction memory.

For me, this paper is also personally meaningful because it connects several topics I care about: dependable computer systems, hardware/software reliability, RISC-V-based experimentation, and practical validation beyond simulation. I am very happy to see Elijah’s work reaching this milestone.

Congratulations again to Elijah and all co-authors!