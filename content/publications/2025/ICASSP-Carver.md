---
title: "Carver: Learning to Reconstruct Right Ventricle from Sparse Multi-View 2D Echocardiograms"
FirstAuthor:
- Yida Li
- Jun Shi
OtherAuthors:
- Zhaohui Wang
- Tiantong Wang
- Ziqi Zhu
- Minfan Zhao

ConfJournal: "IEEE International Conference on Acoustics, Speech and Signal Processing"
ConfJournalAbbr: ICASSP
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2025
Award: ""
Abstract: "We design a dual-aware network incorporating prior contour information to enhance learning representation. We conduct extensive experiments on an echocardiography dataset containing 1,278 instances to validate the effectiveness of the proposed method"
KeyWords:
- Deep learning
- Right ventricle reconstruction
- Multi-view echocardiogram
- Dual-aware network

Link: https://ieeexplore.ieee.org/abstract/document/10889543/ # 官网链接 
PDF: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10889543 # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Accurate 3D reconstruction of the right ventricle from multi-view echocardiograms is crucial for the quantitative diagnosis of cardiac diseases. However, existing methods often fail to deliver satisfactory results due to the structural complexity of the right ventricle and the sparsity of non-parallel ultrasound views. In this paper, we propose an efficient reconstruction method named Carver, which redefines 3D reconstruction of the right ventricle as a voxel-wise dense prediction task for the first time. The core idea lies in using a deep neural network to learn the end-to-end deformation from a coarse geometric convex hull to a fine structure of the right ventricle, similar to carving. To improve the reconstruction accuracy and robustness, we design a dual-aware network incorporating prior contour information to enhance learning representation. We conduct extensive experiments on an echocardiography dataset containing 1,278 instances to validate the effectiveness of the proposed method. Experimental results demonstrate that Carver outperforms existing state-of-the-art methods, achieving a Volume Similarity (VS) of 98.75%, a Dice Similarity Coefficient (DSC) of 97.80%, a Hausdorff Distance (HD) of 4.96, and a Root Mean Square Error (RMSE) of 0.013 for the ejection fraction, while maintaining considerable robustness even with sparser inputs. The code is available at https://github.com/ustclyd/Carver.
