---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second-year master's student at Xidian University, advised by Prof. De Cheng and Prof. Nannan Wang. Prior to this, I received my bachelor degree in Aerospace Science and Technology in 2023. My research interests are in computer vision and multi-modal learning, with specific interest in person re-identification, continual learning, parameter-efficient fine-tuning, unsupervised and semi-supervised learning, noisy label learning, etc.

[Email: lfhe@stu.xidian.edu.cn](lfhe@stu.xidian.edu.cn) / [Github](https://github.com/FranklinLingfeng) / [Google scholar](https://scholar.google.com/citations?user=bUCPpbAAAAAJ&hl=zh-CN)

## Publications (*equal contribution; only papers as first authors are included; double click to view abstract)
---

### Efficient bilateral cross-modality cluster matching for unsupervised visible-infrared person reid

De Cheng*, Lingfeng He*, Nannan Wang, Shizhou Zhang, Zhen Wang, Xinbo Gao
*Proceedings of the 31st ACM international conference on multimedia (ACM MM), 2023 (CCF-A, Oral)*

[PDF](images/MBCCM.pdf) [Arxiv](https://arxiv.org/pdf/2305.12673) [code](https://github.com/FranklinLingfeng/MBCCM-master-MM-23)

<div style="display: flex; align-items: flex-start; margin-top: 10px;">
  <img src="images/MBCCM.png" alt="MBCCM Framework" width="300" style="margin-right: 20px;">
  <p>
  <details>
  <summary><strong>▼ Abstract</strong></summary>
    Unsupervised visible-infrared person re-identification (USL-VI-ReID) aims to match pedestrian images of the same identity from different modalities without annotations. Existing works mainly focus on alleviating the modality gap by aligning instance-level features of the unlabeled samples. However, the relationships between crossmodality clusters are not well explored. To this end, we propose a novel bilateral cluster matching-based learning framework to reduce the modality gap by matching cross-modality clusters. Specifically, we design a Many-to-many Bilateral Cross-Modality Cluster Matching (MBCCM) algorithm through optimizing the maximum matching problem in a bipartite graph. Then, the matched pairwise clusters utilize shared visible and infrared pseudo-labels during the model training. Under such a supervisory signal, a ModalitySpecific and Modality-Agnostic (MSMA) contrastive learning framework is proposed to align features jointly at a cluster-level. Meanwhile, the cross-modality Consistency Constraint (CC) is proposed to explicitly reduce the large modality discrepancy. Extensive experiments on the public SYSU-MM01 and RegDB datasets demonstrate the effectiveness of the proposed method, surpassing state-of-theart approaches by a large margin of 8.76% mAP on average.
  <details>
  </p>
</div>



