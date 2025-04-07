---
title: "Deep learning promoted target volumes delineation of total marrow and total lymphoid irradiation for accelerated radiotherapy: A multi-institutional study"
FirstAuthor:
- Xudong Xue
- Jun Shi
OtherAuthors:
- Hui Zeng
- Bing Yan
- Lei Liu
- Dazhen Jiang
- Xiaoyong Wang
- Hui Liu
- Man Jiang
- Jianjun Shen
- Hong An
- An Liu

ConfJournal: "Physica Medica"
ConfJournalAbbr: Physica Medica
IsAConference: "no" # 会议填yes，期刊写 no
CCFLevel: "A" 
JournalLabel: "SCI Q1, IF=3.2" # SCI Q1, IF=5.7
Year: 2024
Award: ""
Abstract: ""
KeyWords: 
- MI
- TMLI
- Auto-segmentation
- Deep learning

Link: https://www.sciencedirect.com/science/article/pii/S1120179724001881 # 官网链接 
PDF: # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Background and purpose
One of the current roadblocks to the widespread use of Total Marrow Irradiation (TMI) and Total Marrow and Lymphoid Irradiation (TMLI) is the challenging difficulties in tumor target contouring workflow. This study aims to develop a hybrid neural network model that promotes accurate, automatic, and rapid segmentation of multi-class clinical target volumes.
Materials and methods
Patients who underwent TMI and TMLI from January 2018 to May 2022 were included. Two independent oncologists manually contoured eight target volumes for patients on CT images. A novel Dual-Encoder Alignment Network (DEA-Net) was developed and trained using 46 patients from one internal institution and independently evaluated on a total of 39 internal and external patients. Performance was evaluated on accuracy metrics and delineation time.
Results
The DEA-Net achieved a mean dice similarity coefficient of 90.1 % ± 1.8 % for internal testing dataset (23 patients) and 91.1 % ± 2.5 % for external testing dataset (16 patients). The 95 % Hausdorff distance and average symmetric surface distance were 2.04 ± 0.62 mm and 0.57 ± 0.11 mm for internal testing dataset, and 2.17 ± 0.68 mm, and 0.57 ± 0.20 mm for external testing dataset, respectively, outperforming most of existing state-of-the-art methods. In addition, the automatic segmentation workflow reduced delineation time by 98 % compared to the conventional manual contouring process (mean 173 ± 29 s vs. 12168 ± 1690 s; P < 0.001). Ablation study validate the effectiveness of hybrid structures.
Conclusion
The proposed deep learning framework achieved comparable or superior target volume delineation accuracy, significantly accelerating the radiotherapy planning process.
