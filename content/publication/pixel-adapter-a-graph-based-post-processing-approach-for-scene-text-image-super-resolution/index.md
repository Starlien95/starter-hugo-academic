---
title: "Pixel Adapter: A Graph-Based Post-Processing Approach for Scene Text
  Image Super-Resolution"
publication_types:
  - "1"
authors:
  - Wenyu Zhang
  - Xin Deng
  - Baojun Jia
  - admin
  - Yifan Chen
  - jin Ma
  - Qing Ding
  - Xinming Zhang
publication: ""
publication_short: ACMMM 2023
abstract: Current Scene text image super-resolution approaches primarily focus
  on extracting robust features from low-resolution images and optimizing the
  loss function during training to generate super-resolution images. However,
  the previous method neglects the upsampling process within the model leading
  to a decline in image quality. To address this issue, our method not only
  emphasizes robust feature extraction but also innovatively introduces a
  post-processing module. Specifically, We propose the Pixel Adapter Module
  (PAM), a graph attention-based approach that efficiently aggregates pixel
  features, smoothing local regions and mitigating upsampling-induced
  discontinuity. PAM outperforms prior graph-based attention mechanisms,
  offering 2-3 orders of magnitude faster processing and reduced memory
  consumption. We propose a multi-layer perception (MLP) based Sequential
  Residual Block, which enhances the feature extraction capabilities and
  provides robust features for the upsampling module. Furthermore, to perceive
  local image contours, we introduce the Local Contour Awareness Loss, utilizing
  the Histogram of Oriented Gradients feature as the reconstruction target. This
  ensures the model prioritizes the retention of geometric and optical
  deformations in the image. Comprehensive experiments on TextZoom demonstrate
  that our proposed method generates high-quality super-resolution images,
  surpassing existing methods in recognition accuracy. For single-stage and
  multi-stage strategies, we achieved improvements of 0.7\% and 2.6\%,
  respectively, increasing the performance from 52.6\% and 53.7\% to 53.3\% and
  56.3\%. The code is available at https://anonymous.4open.science/r/RTSRN-FD14.
draft: false
featured: false
image:
  filename: framework.png
  focal_point: Smart
  preview_only: false
date: 2023-08-06T02:38:03.393Z
---
