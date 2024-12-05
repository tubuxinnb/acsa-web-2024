---
title: "DB-SpGEMM: A Massively Distributed Block-Sparse Matrix-Matrix Multiplication for Linear-Scaling DFT Calculations"
FirstAuthor:
- Zhong Zheng
OtherAuthors:
- Junshi Chen
- Yang Zhao
- Longsheng Song
- Xinming Qin
- Hong An

ConfJournal: "International Conference on Parallel Processing"
ConfJournalAbbr: ICPP
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2024
Award: ""
Abstract: "We have developed a distributed block-sparse matrix-matrix multiplication (DB-SpGEMM) algorithm for large-scale DFT calculations. Through deep optimizations in distributed matrix storage, computational task decomposition, asynchronous task scheduling, and load balancing, we have implemented a linear-scaling method based on this algorithm within the discontinuous Galerkin density functional theory (DGDFT)"
KeyWords:
- Density functional theory
- Block-sparse matrix
- Matrix-matrix multiplications
- New-generation sunway supercomputer

Link: https://dl.acm.org/doi/10.1145/3673038.3673159 # 官网链接 
PDF:  # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Linear-scaling O(N) density functional theory (DFT) represents a significant advancement in the field of computational materials science, especially for simulations of large systems where traditional cubic-scaling methods become computationally prohibitive. The core operation in O(N) methods is sparse general matrix-matrix multiplication (SpGEMM), which is the major performance bottleneck. To enhance the computational efficiency of SpGEMM, it is crucial to consider the inherent sparse pattern of these matrices. Targeting block-sparse matrices with moderate block sizes and regular block shapes, we have developed a distributed block-sparse matrix-matrix multiplication (DB-SpGEMM) algorithm for large-scale DFT calculations. Through deep optimizations in distributed matrix storage, computational task decomposition, asynchronous task scheduling, and load balancing, we have implemented a linear-scaling method based on this algorithm within the discontinuous Galerkin density functional theory (DGDFT). On the new Sunway supercomputer, our approach achieves a 8 ∼ 10x speedup compared to the original version on monolayer phosphorene systems, and demonstrates superior scalability.