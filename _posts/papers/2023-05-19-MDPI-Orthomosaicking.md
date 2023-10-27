---
title:  "Orthomosaicking Thermal Drone Images of Forests via Simultaneously Acquired RGB Images"
layout: post
categories: publications
img: mdpi.png
---
Rudraksh Kapil, Guillermo Castilla, Seyed Mojtaba Marvasti-Zadeh, Devin Goodsman, Nadir Erbilgin, and Nilanjan Ray

#### *Feature Paper in Forest Collection, MDPI Remote Sensing Journal, Vol. 15, No. 10, p. 2653, 2023*



**Abstract**: Operational forest monitoring often requires fine-detail information in the form of an orthomosaic, created by stitching overlapping nadir images captured by aerial platforms such as drones. RGB drone sensors are commonly used for low-cost, high-resolution imaging that is conducive to effective orthomosaicking, but only capture visible light. Thermal sensors, on the other hand, capture long-wave infrared radiation, which is useful for early pest detection among other applications. However, these lower-resolution images suffer from reduced contrast and lack of descriptive features for successful orthomosaicking, leading to gaps or swirling artifacts in the orthomosaic. To tackle this, we propose a thermal orthomosaicking workflow that leverages simultaneously acquired RGB images. The latter are used for producing a surface mesh via structure from motion, while thermal images are only used to texture this mesh and yield a thermal orthomosaic. Prior to texturing, RGB-thermal image pairs are co-registered using an affine transformation derived from a machine learning technique. On average, the individual RGB and thermal images achieve a mutual information of 0.2787 after co-registration using our technique, compared to 0.0591 before co-registration, and 0.1934 using manual co-registration. We show that the thermal orthomosaic generated from our workflow (1) is of better quality than other existing methods, (2) is geometrically aligned with the RGB orthomosaic, (3) preserves radiometric information (i.e., surface temperatures) from the original thermal imagery, and (4) enables easy transfer of downstream tasks—such as tree crown detection from the RGB to the thermal orthomosaic. We also provide an open-source tool that implements our workflow to facilitate usage and further development.

<div class="button-container">
  <div class="more"><a href="https://doi.org/10.3390/rs15102653">View on MDPI</a></div>
  <div class="more"><a href="https://github.com/rudrakshkapil/Integrated-RGB-Thermal-Orthomosaicing">GitHub Repo</a></div>
</div>


<div style="display:flex;justify-content:center;align-items:center">
  <img src="{{ site.baseurl }}/resources/publications/{{ page.img }}" alt="{{ page.alt }}" style="width:90%;height:auto;justify-content:center">
</div>

