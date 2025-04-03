---
title: "PWDFT-SW: Extending the Limit of Plane-Wave DFT Calculations to 16K Atoms on the New Sunway Supercomputer"
FirstAuthor:
- Qingcai Jiang
- Zhenwei Cao
OtherAuthors:
- Junshi Chen
- Xinming Qin
- Wei Hu
- Hong An
- Jinlong Yang

ConfJournal: "IEEE Transactions on Parallel and Distributed Systems"
ConfJournalAbbr: TPDS
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "A" 
Year: 2024
Award: ""
Abstract: "First-principles density functional theory (DFT) with plane wave (PW) basis set is the most widely used method in quantum mechanical material simulations due to its advantages in accuracy and universality. However, a perceived drawback of PW-based DFT calculations is their substantial computational cost and memory usage, which currently limits their ability to simulate large-scale complex systems containing thousands of atoms. This situation is exacerbated in the new Sunway supercomputer, where each process is limited to a mere 16 GB of memory. Herein, we present a novel parallel implementation of plane wave density functional theory on the new Sunway supercomputer (PWDFT-SW). PWDFT-SW fully extracts the benefits of Sunway supercomputer by extensively refactoring and calibrating our algorithms to align with the system characteristics of the Sunway system. Through extensive numerical experiments, we demonstrate that our methods can substantially decrease both computational costs and memory usage. Our optimizations translate to a speedup of 64.8x for a physical system containing 4,096 silicon atoms, enabling us to push the limit of PW-based DFT calculations to large-scale systems containing 16,384 carbon atoms."
KeyWords:
- Quantum mechanics
- Plane-wave density functional theory
- New Sunway supercomputer
- Parallel implementation

Link: # 官网链接 
PDF:  # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

First-principles density functional theory (DFT) with plane wave (PW) basis set is the most widely used method in quantum mechanical material simulations due to its advantages in accuracy and universality. However, a perceived drawback of PW-based DFT calculations is their substantial computational cost and memory usage, which currently limits their ability to simulate large-scale complex systems containing thousands of atoms. This situation is exacerbated in the new Sunway supercomputer, where each process is limited to a mere 16 GB of memory. Herein, we present a novel parallel implementation of plane wave density functional theory on the new Sunway supercomputer (PWDFT-SW). PWDFT-SW fully extracts the benefits of Sunway supercomputer by extensively refactoring and calibrating our algorithms to align with the system characteristics of the Sunway system. Through extensive numerical experiments, we demonstrate that our methods can substantially decrease both computational costs and memory usage. Our optimizations translate to a speedup of 64.8x for a physical system containing 4,096 silicon atoms, enabling us to push the limit of PW-based DFT calculations to large-scale systems containing 16,384 carbon atoms.
