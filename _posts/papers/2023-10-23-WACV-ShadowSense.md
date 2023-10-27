---
title:  "ShadowSense: Unsupervised Domain Adaptation and Feature Fusion for Shadow-Agnostic Tree Crown Detection from RGB-Thermal Drone Imagery"
layout: post
categories: publications
img: wacv-ShadowSense.png
---

Rudraksh Kapil, Seyed Mojtaba Marvasti-Zadeh, Nadir Erbilgin, and Nilanjan Ray

#### *in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024. In print.*


**Abstract**: Accurate detection of individual tree crowns from remote sensing data poses a significant challenge due to the dense nature of forest canopy and the presence of diverse environmental variations, e.g., overlapping canopies, occlusions, and varying lighting conditions. Additionally, the lack of data for training robust models adds another limitation in effectively studying complex forest conditions. This paper presents a novel method for detecting shadowed tree crowns and provides a challenging dataset comprising roughly 50k paired RGB-thermal images to facilitate future research for illumination-invariant detection. The proposed method (ShadowSense) is entirely self-supervised, leveraging domain adversarial training without source domain annotations for feature extraction and foreground feature alignment for feature pyramid networks to adapt domain-invariant representations by focusing on visible foreground regions, respectively. It then fuses complementary information of both modalities to effectively improve upon the predictions of an RGB-trained detector and boost the overall accuracy. Extensive experiments demonstrate the superiority of the proposed method over both the baseline RGB-trained detector and state-of-the-art techniques that rely on unsupervised domain adaptation or early image fusion.



<div class="button-container" style="margin-bottom:10px">
  <div class="more"><a href="https://arxiv.org/abs/2310.16212">View on arXiv</a></div>
  <div class="more"><a href="{{ site.url }}/resources/publications/wacv_supplementary.pdf">Supplementary Material</a></div>
  <div class="more"><a href="https://github.com/rudrakshkapil/ShadowSense">GitHub Repo</a></div>
</div>


<div style="display:flex;justify-content:center;align-items:center">
  <img src="{{ site.baseurl }}/resources/projects/{{ page.img }}" alt="{{ page.alt }}" style="width:90%;height:auto;justify-content:center">
</div>

