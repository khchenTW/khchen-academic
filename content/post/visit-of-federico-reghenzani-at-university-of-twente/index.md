---
title: Visit of Federico Reghenzani at University of Twente
date: 2025-09-10T19:22:57.484Z
draft: false
featured: false
image:
  filename: featured.jpeg
  focal_point: Smart
  preview_only: false
---
On September 3rd, 2025, together with **Marco Ottavi**, lead of the *Dependable Computing Systems* group, I had the pleasure of hosting **Federico Reghenzani**, Assistant Professor from the **HEAP Lab at Politecnico di Milano**. His talk, *“When Software Meets Radiation: Compiler-level Hardening and Testing”*, offered valuable insights into **Software-Implemented Hardware Fault Tolerance (SIHFT)** and its experimental evaluation through fault injection campaigns—a topic closely connected to my long-standing research interest since my PhD.

Federico introduced **ASPIS**, a set of LLVM compiler passes that transparently add SIHFT mechanisms (such as data replication and control-flow graph signatures) while preserving compiler optimizations. He further presented experimental results obtained with **laser facilities, radioactive sources, and particle accelerators**, showing how ASPIS can drastically reduce silent data corruptions, albeit at the cost of execution overhead.

During the visit, we identified two promising directions for collaboration:

* **Hardware generation of signature calculation for control-flow execution**\
  Extending ASPIS’ control-flow protection by offloading signature computations to dedicated hardware accelerators.
* **FPGA-based fault injection for SIHFT evaluation**\
  Exploiting our FPGA-based injection infrastructure to pinpoint which hardware features remain insufficiently protected by SIHFT, paving the way for a **hardware/software co-design approach** to reinforce these weak points.

We look forward to pursuing this collaboration and advancing **efficient, compiler-assisted, and hardware-supported fault tolerance** for real-time and safety-critical systems.