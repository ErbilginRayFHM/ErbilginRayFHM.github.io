---
title:  "Training-based Model Refinement and Representation Disagreement for Semi-Supervised Object Detection"
layout: post
categories: publications
img: wacv-TMR-RD.png
---

Seyed Mojtaba Marvasti-Zadeh, Nilanjan Ray, Nadir Erbilgin 

#### *in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024. In print.*


**Abstract**: Semi-supervised object detection (SSOD) can incorporate limited labeled data and large amounts of unlabeled data to improve the performance and generalization of existing object detectors. Despite many advances, recent SSOD methods are still challenged by noisy/misleading pseudo-labels, classical exponential moving average (EMA) strategy, and the consensus of Teacher-Student models in the latter stages of training. This paper proposes a novel training-based model refinement (TMR) stage and a simple yet effective representation disagreement (RD) strategy to address the limitations of classical EMA and the consensus problem. The TMR stage of Teacher-Student models optimizes the lightweight scaling operation to refine the model's weights and prevent overfitting or forgetting learned patterns from unlabeled data. Meanwhile, the RD strategy helps keep these models diverged to encourage the student model to explore complementary representations. In addition, we use cascade regression to generate more reliable pseudo-labels for supervising the student model. Extensive experiments demonstrate the superior performance of our approach over state-of-the-art SSOD methods. Specifically, the proposed approach outperforms the Unbiased-Teacher method by an average mAP margin of 4.6% and 5.3% when using partially-labeled and fully-labeled data on the MS-COCO dataset, respectively.


<div class="button-container" style="margin-bottom:10px">
  <div class="more"><a href="https://arxiv.org/abs/2307.13755">View on arXiv</a></div>
</div>


<div style="display:flex;justify-content:center;align-items:center">
  <img src="{{ site.baseurl }}/resources/projects/{{ page.img }}" alt="{{ page.alt }}" style="width:90%;height:auto;justify-content:center">
</div>



