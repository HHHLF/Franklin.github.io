---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
body {
    font-family: "Times New Roman", Times, serif;
}
</style>

I am a second-year master's student at Xidian University, advised by Prof. De Cheng and Prof. Nannan Wang. Prior to this, I received my bachelor degree in Aerospace Science and Technology in 2023. My research interests are in computer vision and multi-modal learning, with specific interest in person re-identification, continual learning, parameter-efficient fine-tuning, unsupervised and semi-supervised learning, noisy label learning, etc.

[Email: lfhe@stu.xidian.edu.cn](lfhe@stu.xidian.edu.cn) / [Github](https://github.com/FranklinLingfeng) / [Google scholar](https://scholar.google.com/citations?user=bUCPpbAAAAAJ&hl=zh-CN)

## Publications 

(*equal contribution; only papers as first authors are included; double click to view abstract)

---

<div style="display: flex; align-items: flex-start; margin-top: 10px;">
  <img src="images/MBCCM.png" alt="MBCCM Framework" width="300" style="margin-right: 20px;">
  
  <div>
    <strong>Efficient Bilateral Cross-Modality Cluster Matching for Unsupervised Visible-Infrared Person Re-ID</strong><br>
    De Cheng*, <strong>Lingfeng He*</strong>, Nannan Wang, Shizhou Zhang, Zhen Wang, Xinbo Gao<br>
    <em>Proceedings of the 31st ACM International Conference on Multimedia (ACM MM), 2023 (CCF-A, Oral)</em><br><br>

    <a href="images/MBCCM.pdf">[PDF]</a> 
    <a href="https://arxiv.org/pdf/2305.12673">[Arxiv]</a> 
    <a href="https://github.com/FranklinLingfeng/MBCCM-master-MM-23">[Code]</a>

  <details style="margin-top:10px;">
    <summary><strong>Abstract</strong></summary>
    <div style="background-color: #f5f5f5; padding: 10px; border-radius: 5px; border: 1px solid #ddd; font-size: 0.85em; line-height: 1.3;">
      Unsupervised visible-infrared person re-identification (USL-VI-ReID) aims to match pedestrian images of the same identity from different modalities without annotations. Existing works mainly focus on alleviating the modality gap by aligning instance-level features of the unlabeled samples. However, the relationships between cross-modality clusters are not well explored. To this end, we propose a novel bilateral cluster matching-based learning framework to reduce the modality gap by matching cross-modality clusters. Specifically, we design a Many-to-many Bilateral Cross-Modality Cluster Matching (MBCCM) algorithm through optimizing the maximum matching problem in a bipartite graph. Then, the matched pairwise clusters utilize shared visible and infrared pseudo-labels during the model training. Under such a supervisory signal, a Modality-Specific and Modality-Agnostic (MSMA) contrastive learning framework is proposed to align features jointly at a cluster-level. Meanwhile, the cross-modality Consistency Constraint (CC) is proposed to explicitly reduce the large modality discrepancy. Extensive experiments on the public SYSU-MM01 and RegDB datasets demonstrate the effectiveness of the proposed method, surpassing state-of-the-art approaches by a large margin of 8.76% mAP on average.
    </div>
  </details>
  </div>
</div>



