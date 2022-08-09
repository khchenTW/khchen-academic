---
title: "Softwear: Software-only in-memory wear-leveling for non-volatile main memory"
publication_types:
  - "2"
authors:
  - Christian Hakert
  - Kuan-Hsun Chen
  - Paul R Genssler
  - Georg von der Brüggen
  - Lars Bauer
  - Hussam Amrouch
  - Jian-Jia Chen
  - Jörg Henkel
doi: 10.48550/arXiv.2004.03244
publication: arXiv preprint arXiv:2004.03244
publication_short: arXiv preprint arXiv:2004.03244
abstract: >-
  Several emerging technologies for byte-addressable non-volatile memory (NVM)
  have been considered to replace DRAM as the main memory in computer systems
  during the last years. The disadvantage of a lower write endurance, compared
  to DRAM, of NVM technologies like Phase-Change Memory (PCM) or Ferroelectric
  RAM (FeRAM) has been addressed in the literature. As a solution, in-memory
  wear-leveling techniques have been proposed, which aim to balance the
  wear-level over all memory cells to achieve an increased memory lifetime.
  Generally, to apply such advanced aging-aware wear-leveling techniques
  proposed in the literature, additional special hardware is introduced into the
  memory system to provide the necessary information about the cell age and thus
  enable aging-aware wear-leveling decisions.

  This paper proposes software-only aging-aware wear-leveling based on common CPU features and does not rely on any additional hardware support from the memory subsystem. Specifically, we exploit the memory management unit (MMU), performance counters, and interrupts to approximate the memory write counts as an aging indicator. Although the software-only approach may lead to slightly worse wear-leveling, it is applicable on commonly available hardware. We achieve page-level coarse-grained wear-leveling by approximating the current cell age through statistical sampling and performing physical memory remapping through the MMU. This method results in non-uniform memory usage patterns within a memory page. Hence, we further propose a fine-grained wear-leveling in the stack region of C / C++ compiled software.

  By applying both wear-leveling techniques, we achieve up to 78.43% of the ideal memory lifetime, which is a lifetime improvement of more than a factor of 900 compared to the lifetime without any wear-leveling.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-04-07T14:00:48.194Z
---
