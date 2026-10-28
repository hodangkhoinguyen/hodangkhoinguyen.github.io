---
permalink: /
title: "Nguyen Ho"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year PhD student in Computer Science at George Mason University (GMU), advised by [Prof. ThanhVu Nguyen](https://github.com/nguyenthanhvuh/).
My research focuses on the reliability of AI and optimization software: verifying deep neural networks (DNNs) and testing the solvers that verification tools depend on.

Research highlights
======
* **Testing MILP solvers.** Built a metamorphic testing framework with an exact, certificate-backed oracle for Gurobi, SCIP, HiGHS, CBC, and GLPK. Across about 85,000 solver runs it found 36 defects, 26 of them previously unknown; developers have confirmed 4 and fixed 4 so far.
* **Bit-flip fault verification.** Developed two GPU-accelerated verifiers for quantized DNNs under hardware bit-flip faults. OrBit solves 2.4× more benchmarks than the state-of-the-art tool, and mBFV verifies networks with up to 1.15M parameters under multiple simultaneous weight flips.
* **NeuralSAT.** Contributor to [NeuralSAT](https://github.com/dynaroars/neuralsat), a DPLL(T)-based DNN verifier ranked 2nd in the International Verification of Neural Networks Competition (VNN-COMP) in 2024 and 2025.

I am also a Graduate Teaching Assistant for CS 310 (Data Structures) at GMU.

Before GMU
======
I received my B.S. in Computer Science from the University of California, Davis (UC Davis) in 2023.
During my undergraduate studies, I contributed to educational and community projects including [rvcodec.js](https://luplab.gitlab.io/rvcodecjs/) under the supervision of Professor Porquet,
[Profficient](https://codelabdavis.medium.com/introduction-ddb70fec369a) at CodeLab,
and [Colorflix](https://github.com/hodangkhoinguyen/Colorflix-Backend) & [TaskCollab](https://github.com/hodangkhoinguyen/TaskCollab) at Google Developer Student Club @ UC Davis.

After graduation, I worked as a software developer at the Ronald Lab (UC Davis), where I built and maintained [KitBase](https://kitbase.ucdavis.edu/), an open-access rice genomics platform described in a 2026 article in *Database*, and developed pipelines for rice mutation analysis.
