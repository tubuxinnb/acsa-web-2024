---
title: "Multi-level Load Balancing Strategies for Massively Parallel Smoothed Particle Hydrodynamics Simulation"
FirstAuthor:
- Yi Zhang
- Ziyu Zhang
OtherAuthors:
- Yang Zhao
- Junshi Chen
- Hong An
- Zhanming Wang
- Longkui Che

ConfJournal: "International Conference on Parallel Processing"
ConfJournalAbbr: ICPP
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2024
Award: ""
Abstract: "We propose a novel SPH implementation leveraging multi-level parallelism and a corresponding three-level load balancing strategy. Our load balancing approach comprises: (1) a process-level domain decomposition algorithm based on an improved 1D partitioning exact algorithm; (2) an adaptive recursive cell subdivision method; (3) a fine-grained dynamic thread-level task scheduling strategy."
KeyWords:
- Load balance
- Smoothed particle hydrodynamics
- Many-core computing

Link: https://dl.acm.org/doi/10.1145/3673038.3673090 # 官网链接 
PDF:  # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

In the field of computational fluid dynamics, Smoothed Particle Hydrodynamics (SPH) serves as a powerful tool for investigating complex fluid interactions and instabilities. For the practical SPH simulation of large-scale fluid phenomena such as tsunamis, volcanic eruptions, and planetary collisions, it typically requires billions of particles, as the numerical resolution increases proportionally with the number of particles. To efficiently conduct large-scale SPH simulations on modern supercomputers with massive many-core processors, we propose a novel SPH implementation leveraging multi-level parallelism and a corresponding three-level load balancing strategy. Our load balancing approach comprises: (1) a process-level domain decomposition algorithm based on an improved 1D partitioning exact algorithm; (2) an adaptive recursive cell subdivision method; (3) a fine-grained dynamic thread-level task scheduling strategy. Our experiment uses 1 billion particles to simulate converging Richtmyer–Meshkov instability and verifies the effect of load balancing on new Sunway supercomputer. As the shockwave converges on the central interface area, our load balancing strategy breaks the bottleneck constraints on the slowest node, increases the balance of computational loads between nodes from 30.01% to 91.48%, and achieves a 2.8 × improvement in computational performance. Finally, our implementation enables each CPU to handle 10 million particles and scale from 1 CPU to 100,000 CPUs (in total 39 million cores with 1 trillion particles) with a performance of 80.4% parallel efficiency.