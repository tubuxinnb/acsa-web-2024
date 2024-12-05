---
title: "Predictive Accuracy-Based Active Learning for Medical Image Segmentation"
FirstAuthor:
- Jun Shi
OtherAuthors:
- Shulan Ruan
- Ziqi Zhu
- Minfan Zhao
- Hong An
ConfJournal: "International Joint Conference on Artificial Intelligence"
ConfJournalAbbr: IJCAI
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "A" 
Year: 2024
Award: ""
Abstract: "We propose an efficient Predictive Accuracy-based Active Learning (PAAL) method for medical image segmentation, first introducing predictive accuracy to define uncertainty. Specifically, PAAL mainly consists of an Accuracy Predictor (AP) and a Weighted Polling Strategy (WPS)."
KeyWords:
- Machine Learning
- Computer Vision
- Uncertainty in AI
Link: https://www.ijcai.org/proceedings/2024/540 # 官网链接 
PDF:  # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Active learning is considered a viable solution to alleviate the contradiction between the high dependency of deep learning-based segmentation methods on annotated data and the expensive pixel-level annotation cost of medical images. However, most existing methods suffer from unreliable uncertainty assessment and the struggle to balance diversity and informativeness, leading to poor performance in segmentation tasks. In response, we propose an efficient Predictive Accuracy-based Active Learning (PAAL) method for medical image segmentation, first introducing predictive accuracy to define uncertainty. Specifically, PAAL mainly consists of an Accuracy Predictor (AP) and a Weighted Polling Strategy (WPS). The former is an attached learnable module that can accurately predict the segmentation accuracy of unlabeled samples relative to the target model with the predicted posterior probability. The latter provides an efficient hybrid querying scheme by combining predicted accuracy and feature representation, aiming to ensure the uncertainty and diversity of the acquired samples. Extensive experiment results on multiple datasets demonstrate the superiority of PAAL. PAAL achieves comparable accuracy to fully annotated data while reducing annotation costs by approximately 50% to 80%, showcasing significant potential in clinical applications. The code is available at https://github.com/shijun18/PAAL-MedSeg.