---
permalink: /
title: "Harim Kim"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I recieved my M.S. degree in Computer Science at [Handong Global University](https://handong.edu/) under the supervision of [Prof. Charmgil Hong](https://charmgil.github.io/) in [Handong Artificial Intelligence Lab. (HAIL)](https://hail.handong.edu/), and I am currently **seeking Ph.D. opportunities**.

My current research interests lie in developing **intent-driven deep learning frameworks** to address fundamental challenges in medical AI.

In particular, I am interested in:
- Exploring **multimodal data fusion** strategies for robust and informative representation learning
- Constructing **anomaly detection** techniques informed by latent space understanding 

For more details about my academic background, publications, and research experiences, please refer to [Resume](/cv/) page.

---

Selected Projects
======

This section introduces a selection of representative research projects. For each topic, I provide a brief overview, a description of the most recent publication, and a list of prior related publications.

<div class="selected-block"></div>

<div class="project-block">

<h2>Integrating Multimodal Medical Data</h2>

<div class="swiper project-swiper" id="mmmd-swiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
        <a href="/assets/images/selected/Multimodal/diff3m_visualization.jpg"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Multimodal/diff3m_visualization.jpg" alt="Diff3M Visaulization Results">
        </a>
    </div>
    <div class="swiper-slide">
        <a href="/assets/images/selected/Multimodal/diff3m_framework.jpg"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Multimodal/diff3m_framework.jpg" alt="Diff3M Entire Framework">
        </a>
    </div>
    <div class="swiper-slide">
        <a href="/assets/images/selected/Multimodal/diff3m_modules.jpg"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Multimodal/diff3m_modules.jpg" alt="Diff3M Proposed Modules">
        </a>
    </div>
  </div>
</div>

To build more reliable and explainable medical AI, this project focuses on designing deep learning mechanisms that effectively fuse and utilize multimodal medical data. The goal is to improve disease prediction, enable early detection, and support the discovery of potential biomarkers.

<hr class="project-divider">

<h3 class="project-subtitle">• Most Recent Publication •</h3>

<div class="pub-card pub-card--wide">

  <!-- Row 1: icon + title (same row) -->
  <img class="pub-icon" src="/assets/images/selected/Multimodal/diff3m.jpg" alt="Diff3M icon">

  <div class="pub-head">
    <div class="pub-title">
      <a href="https://link.springer.com/chapter/10.1007/978-3-032-04947-6_23">[Kim et al.] Harnessing EHRs for Diffusion-based Anomaly Detection on Chest X-rays (MICCAI, 2025) - Early Accepted (Top 9%)</a>
    </div>
  </div>

  <!-- Row 2: abstract spans full width -->
  <p class="pub-abstract clamp-3 is-collapsed" data-expandable>
    Unsupervised anomaly detection (UAD) in medical imaging is crucial for identifying pathological abnormalities without requiring extensive labeled data. However, existing diffusion-based UAD models rely solely on imaging features, limiting their ability to distinguish between normal anatomical variations and pathological anomalies. To address this, we propose Diff3M, a multi-modal diffusion-based framework that integrates chest X-rays and structured Electronic Health Records (EHRs) for enhanced anomaly detection. Specifically, we introduce a novel Image-EHR Cross-Attention module to incorporate structured clinical context into the image generation process, improving the model’s ability to differentiate normal from abnormal features. Additionally, we develop a static masking strategy to enhance the reconstruction of normal-like images from anomalies. Extensive evaluations on CheXpert and MIMIC-CXR/IV demonstrate that Diff3M achieves state-of-the-art performance, outperforming existing UAD methods in medical imaging. Our implementation is available at https://github.com/nth221/Diff3M.
  </p>
</div>
</div>






<div class="project-block">

<h2>Reinterpreting for Enhanced Anomaly Detection</h2>

<div class="swiper project-swiper" id="mmmd-swiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
        <a href="/assets/images/selected/Anomaly/Surveillance.mp4"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Anomaly/Surveillance.mp4" alt="Surveillance Video">
        </a>
    </div>
    <div class="swiper-slide">
        <a href="/assets/images/selected/Anomaly/TransPAD_framework.jpg"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Anomaly/TransPAD_framework.jpg" alt="TransPAD Entire Framework">
        </a>
    </div>
    <div class="swiper-slide">
        <a href="/assets/images/selected/Anomaly/TransPAD_visualization.jpg"
     class="glightbox"
     data-gallery="mmmd">
      <img src="/assets/images/selected/Anomaly/TransPAD_visualization.jpg" alt="TransPAD Visualization">
        </a>
    </div>
  </div>
</div>

To detect unpredictable and unusual patterns in real-world data, this project proposes new anomaly detection frameworks by reinterpreting existing deep learning mechanisms. The proposed frameworks can be applied to identify abnormal pathological features in X-rays or abnormal behaviors in surveillance footage.

<hr class="project-divider">

<h3 class="project-subtitle">• Most Recent Publication •</h3>

<div class="pub-card pub-card--wide">

  <!-- Row 1: icon + title (same row) -->
  <img class="pub-icon" src="/assets/images/selected/Anomaly/TransPAD.jpg" alt="TransPAD icon">

  <div class="pub-head">
    <div class="pub-title">
      <a href="https://dl.acm.org/doi/abs/10.1145/3627673.3679859">[Kim et al.] Transformer for Point Anomaly Detection (CIKM, 2024)</a>
    </div>
  </div>

  <!-- Row 2: abstract spans full width -->
  <p class="pub-abstract clamp-3 is-collapsed" data-expandable>
    In data analysis, unsupervised anomaly detection holds an important position for identifying statistical outliers that signify atypical behavior, erroneous readings, or interesting patterns within data. The Transformer model, known for its ability to capture dependencies within sequences, has revolutionized areas such as text and image data analysis. However, its potential for tabular data, where sequence dependencies are not inherently present, remains underexplored. This paper introduces Transformer for Point Anomaly Detection (TransPAD), a novel Transformer-based AutoEncoder framework specifically designed for point anomaly detection. Our method captures interdependencies across entire datasets, addressing the challenges posed with non-sequential, tabular data. It incorporates unique random and criteria sampling strategies for effective training and anomaly identification, and avoids the common pitfall of trivial generalization that affects many conventional methods. By leveraging an attention weight-based anomaly scoring system, TransPAD offers a more precise approach to detect anomalies. Extensive testing on a range of benchmark tabular datasets shows that TransPAD consistently outperforms existing methods. Our source code is available at https://github.com/nth221/TransPAD.
  </p>
</div>
</div>











<!--
- **Harim Kim**, Yuhan Wang, Minkyu Ahn, Heeyoul Choi, Yuyin Zhou, Charmgil Hong. Harnessing EHRs for Diffusion-based Anomaly Detection on Chest X-rays. Medical Image Computing and Computer Assisted Intervention (MICCAI). 2025. (**Early Accepted, Top 9%**) ([paper](https://link.springer.com/chapter/10.1007/978-3-032-04947-6_23), [github](https://github.com/nth221/Diff3M))
- **Harim Kim**, Chang Ha Lee, Charmgil Hong. Transformer for Point Anomaly Detection. ACM International Conference on Information and Knowledge Management (CIKM). 2024. ([paper](https://dl.acm.org/doi/10.1145/3627673.3679859), [github](https://github.com/nth221/TransPAD))
- **Harim Kim**, Minchae Kim, Taewoo Kim, Kyujin Cho, Charmgil Hong. AREST: Attention-Based Red-Light Violation Detection for Safety Technology. IEEE International Conference on Advanced Video and Signal-Based Surveillance (AVSS). 2024. ([paper](https://ieeexplore.ieee.org/document/10672611))
- **Harim Kim**, Chang Ha Lee, Charmgil Hong. VATMAN: Video Anomaly Transformer for Monitoring Accidents and Nefariousness. IEEE International Conference on Advanced Video and Signal-Based Surveillance (AVSS). 2024. ([paper](https://ieeexplore.ieee.org/document/10672570), [github](https://github.com/nth221/vatman))
-->
