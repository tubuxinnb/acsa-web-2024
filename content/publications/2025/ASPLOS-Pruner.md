---
title: "Pruner: A Draft-then-Verify Exploration Mechanism to Accelerate Tensor Program Tuning"
FirstAuthor:
- Liang Qiao
- Jun Shi
OtherAuthors:
- Xiaoyu Hao
- Xi Fang
- Sen Zhang
- Minfan Zhao
- Ziqi Zhu
- Junshi Chen
- Hong An
- Xulong Tang
- Bing Li
- Honghui Yuan
- Xinyang Wang
ConfJournal: "ACM International Conference on Architectural Support for Programming Languages and Operating Systems"
ConfJournalAbbr: ASPLOS
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "A" 
Year: 2025
Award: ""
Abstract: "We propose Pruner and MoA-Pruner. Pruner is a ''Draft-then-Verify'' exploration mechanism that accelerates the schedule search process. Instead of applying the complex learned cost model to all explored candidates, Pruner drafts small-scale potential candidates by introducing a naive Symbol-based Analyzer (draft model), then identifies the best candidates by the learned cost model. MoA-Pruner introduces a Momentum online Adaptation strategy to address the cross-platform online unawareness."
KeyWords:
- Code generation
- Compiler optimization
- Tensor program tuning
Link: https://dl.acm.org/doi/10.1145/3676641.3716269 # 官网链接 
PDF: https://dl.acm.org/doi/pdf/10.1145/3676641.3716269 # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Tensor program tuning is essential for the efficient deployment of deep neural networks. Search-based approaches have demonstrated scalability and effectiveness in automatically finding high-performance programs for specific hardware. However, the search process is often inefficient, taking hours or even days to discover optimal programs due to the exploration mechanisms guided by an accurate but slow-learned cost model. Meanwhile, the learned cost model trained on one platform cannot seamlessly adapt online to another, which we call cross-platform online unawareness. In this work, we propose Pruner and MoA-Pruner. Pruner is a ''Draft-then-Verify'' exploration mechanism that accelerates the schedule search process. Instead of applying the complex learned cost model to all explored candidates, Pruner drafts small-scale potential candidates by introducing a naive Symbol-based Analyzer (draft model), then identifies the best candidates by the learned cost model. MoA-Pruner introduces a Momentum online Adaptation strategy to address the cross-platform online unawareness.
We incorporate Pruner into the TVM and conduct extensive experiments on three GPU-based platforms. Results show considerable speedup in schedule search time. In online tuning scenarios, Pruner and MoA-Pruner achieve an average speedup of 2.6 × and 4.82 × compared to Ansor. In offline tuning scenarios, Pruner achieves an average speedup of 4.75 × and 4.05× compared to TenSet and TLP, respectively. Furthermore, Pruner achieves an average speedup of 4.08 × compared to MetaSchedule on TensorCore.
