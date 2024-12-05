---
title: "Extending the limit of LR-TDDFT on two different approaches: Numerical algorithms and new Sunway heterogeneous supercomputer"
FirstAuthor:
- Qingcai Jiang
OtherAuthors:
- Zhenwei Cao
- Xinhui Cui
- Lingyun Wan
- Xinming Qin
- Huanqi Cao
- Hong An
- Junshi Chen
- Jie Liu
- Wei Hu
- Jinlong Yang

ConfJournal: "Parallel Computing"
ConfJournalAbbr: Parallel Computing
IsAConference: "no" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2024
Award: ""
Abstract: "We present a massively parallel implementation of linear-response TDDFT (LR-TDDFT) and accelerate LR-TDDFT in two different aspects: (1) numerical algorithms on the X86 supercomputer and (2) optimizations on the heterogeneous architecture of the new Sunway supercomputer. Furthermore, we carefully design the parallel data and task distribution schemes to accommodate the physical nature of different computation steps."
KeyWords:
- Quantum mechanics
- Time-dependent density functional theory
- Linear-response
- Iterative eigensolver
- Low-rank approximation
- Parallel implementation

Link: https://www.sciencedirect.com/science/article/pii/S0167819124000231 # 官网链接 
PDF:  # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

First-principles time-dependent density functional theory (TDDFT) is a powerful tool to accurately describe the excited-state properties of molecules and solids in condensed matter physics, computational chemistry, and materials science. However, a perceived drawback in TDDFT calculations is its ultrahigh computational cost O(N^5~N^6) and large memory usage O(N^4) especially for plane-wave basis set, confining its applications to large systems containing thousands of atoms. Here, we present a massively parallel implementation of linear-response TDDFT (LR-TDDFT) and accelerate LR-TDDFT in two different aspects: (1) numerical algorithms on the X86 supercomputer and (2) optimizations on the heterogeneous architecture of the new Sunway supercomputer. Furthermore, we carefully design the parallel data and task distribution schemes to accommodate the physical nature of different computation steps. By utilizing these two different methods, our implementation can gain an overall speedup of 10x and 80x and efficiently scales to large systems up to 4096 and 2744 atoms within dozens of seconds.
