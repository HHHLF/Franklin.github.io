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
  <img src="images/mult.png" alt="MULT Framework" width="300" style="margin-right: 20px;">
  
  <div>
    <strong>Exploring Homogeneous and Heterogeneous Consistent Label Associations for Unsupervised Visible-Infrared Person ReID</strong><br>
    <strong>Lingfeng He</strong>, De Cheng, Nannan Wang, Xinbo Gao<br>
    <em>International Journal of Computer Vision (IJCV), 2024 (CCF-A)</em><br><br>

    <a href="images/mult.pdf">[PDF]</a> 
    <a href="https://arxiv.org/pdf/2402.00672">[Arxiv]</a> 
    <a href="https://github.com/FranklinLingfeng/MULT_for_unsupervised_visible_infrared_ReID">[Code]</a>

  <details style="margin-top:10px;">
    <summary><strong>Abstract</strong></summary>
    <div style="background-color: #f5f5f5; padding: 10px; border-radius: 5px; border: 1px solid #ddd; font-size: 0.85em; line-height: 1.3;">
      Unsupervised visible-infrared person re-identification (USL-VI-ReID) endeavors to retrieve pedestrian images of the same identity from different modalities without annotations. While prior work focuses on establishing cross-modality pseudolabel associations to bridge the modality-gap, they ignore maintaining the instance-level homogeneous and heterogeneous consistency between the feature space and the pseudo-label space, resulting in coarse associations. In response, we introduce
a Modality-Unified Label Transfer (MULT) module that simultaneously accounts for both homogeneous and heterogeneous fine-grained instance-level structures, yielding high-quality cross-modality label associations. It models both homogeneous and heterogeneous affinities, leveraging them to quantify the inconsistency between the pseudo-label space and the feature space, subsequently minimizing it. The proposed MULT ensures that the generated pseudo-labels maintain alignment across modalities while upholding structural consistency within intra-modality. Additionally, a straightforward plug-and-play Online Cross-memory Label Refinement (OCLR) module is proposed to further mitigate the side effects of noisy pseudo-labels while simultaneously aligning different modalities, coupled with an Alternative Modality-Invariant Representation Learning (AMIRL) framework. Experiments demonstrate that our proposed method outperforms existing state-of-the-art USL-VIReID methods, highlighting the superiority of our MULT in comparison to other cross-modality association methods. 
    </div>
  </details>
  </div>
</div>


<div style="display: flex; align-items: flex-start; margin-top: 10px;">
  <img src="images/saclr.png" alt="SACLR Framework" width="300" style="margin-right: 20px;">
  
  <div>
    <strong>Semantic-Aligned Learning with Collaborative Refinement for Unsupervised VI-ReID</strong><br>
    De Cheng*, <strong>Lingfeng He*</strong>, Nannan Wang, Dingwen Zhang, Xinbo Gao<br>
    <em>International Journal of Computer Vision (IJCV), 2025 (CCF-A)</em><br><br>

    <a href="images/saclr.pdf">[PDF]</a> 
    <a href="https://arxiv.org/pdf/2504.19244">[Arxiv]</a> 
    <a href="https://github.com/FranklinLingfeng/code-for-SALCR">[Code]</a>

  <details style="margin-top:10px;">
    <summary><strong>Abstract</strong></summary>
    <div style="background-color: #f5f5f5; padding: 10px; border-radius: 5px; border: 1px solid #ddd; font-size: 0.85em; line-height: 1.3;">
      Unsupervised visible-infrared person re-identification (USL-VI-ReID) seeks to match pedestrian images of the same individual across different modalities without human annotations for model learning. Previous methods unify pseudo-labels of cross-modality images through label association algorithms and then design contrastive learning framework for global feature learning. However, these methods overlook the cross-modality variations in feature representation and pseudo-label distributions brought by fine-grained patterns. This insight results in insufficient modality-shared learning when only global features are optimized. To address this issue, we propose a Semantic-Aligned Learning with Collaborative Refinement (SALCR) framework, which builds up optimization objective for specific fine-grained patterns emphasized by each modality, thereby achieving complementary alignment between the label distributions of different modalities. Specifically, we first introduce a Dual Association with Global Learning (DAGI) module to unify the pseudo-labels of cross-modality instances in a bi-directional manner. Afterward, a Fine-Grained Semantic-Aligned Learning (FGSAL) module is carried out to explore part-level semantic-aligned patterns emphasized by each modality from cross-modality instances. Optimization objective is then formulated based on the semantic-aligned features and their corresponding label space. To alleviate the side-effects arising from noisy pseudo-labels, we propose a Global-Part Collaborative Refinement (GPCR) module to mine reliable positive sample sets for the global and part features dynamically and optimize the inter-instance relationships. Extensive experiments demonstrate the effectiveness of the proposed method, which achieves superior performances to state-of-the-art methods.
    </div>
  </details>
  </div>
</div>


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



