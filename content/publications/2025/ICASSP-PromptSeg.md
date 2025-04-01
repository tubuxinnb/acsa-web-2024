---
title: "PromptSeg: Learning to Segment Medical Image via Visual Prompts"
FirstAuthor:
- Minfan Zhao
- Ziqi Zhu
OtherAuthors:
- Jun Shi
- Zhaohui Wang
- Junshi Chen
- Hong An

ConfJournal: "IEEE International Conference on Acoustics, Speech and Signal Processing"
ConfJournalAbbr: ICASSP
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2025
Award: ""
Abstract: "We propose PromptSeg, an innovative Transformer-based unified segmentation framework for general medical image segmentation tasks. PromptSeg aims to utilize the provided visual prompts to recognize task patterns and learn contextual representations, thereby breaking the restrictions of the task-specific paradigm. When faced with unseen datasets or segmentation targets during inference, our method only requires a few annotated prompt pairs to understand the task and segment the query images without retraining, alleviating the need for large-scale annotation data."
KeyWords:
Link: https://ieeexplore.ieee.org/document/10889700 # 官网链接 
PDF: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10889700 # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Deep learning has made remarkable medical image segmentation advancements, yet its generalization capability across tasks remains challenging. The variety of task objectives, disease-dependent labeling variations, and multi-center data contribute to the poor generalization capacity of task-specific models on unseen tasks, necessitating domain adaptation or fine-tuning. This typically involves data annotation and network retraining, limiting the application of deep learning in clinical practice. In this study, we propose PromptSeg, an innovative Transformer-based unified segmentation framework for general medical image segmentation tasks. PromptSeg aims to utilize the provided visual prompts to recognize task patterns and learn contextual representations, thereby breaking the restrictions of the task-specific paradigm. When faced with unseen datasets or segmentation targets during inference, our method only requires a few annotated prompt pairs to understand the task and segment the query images without retraining, alleviating the need for large-scale annotation data. The experimental results demonstrate that our method outperforms existing state-of-the-art methods and exhibits high generalization capability on multiple unseen tasks. The source code is available at https://github.com/MinfanZhao/PromptSeg.
