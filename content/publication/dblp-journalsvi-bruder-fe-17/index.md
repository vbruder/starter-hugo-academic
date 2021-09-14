---
title: "Prediction-based load balancing and resolution tuning for interactive volume raycasting"
date: 2017-01-01
authors: 
- admin
- "Steffen Frey"
- "Thomas Ertl"
publication_types: ["2"]
abstract: "We present an integrated approach for real-time performance prediction of volume raycasting that we employ for load balancing and sampling resolution tuning. In volume rendering, the usage of acceleration techniques such as empty space skipping and early ray termination, among others, can cause significant variations in rendering performance when users adjust the camera configuration or transfer function. These variations in rendering times may result in unpleasant effects such as jerky motions or abruptly reduced responsiveness during interactive exploration. To avoid those effects, we propose an integrated approach to adapt rendering parameters according to performance needs. We assess performance-relevant data on-the-fly, for which we propose a novel technique to estimate the impact of early ray termination. On the basis of this data, we introduce a hybrid model, to achieve accurate predictions with minimal computational footprint. Our hybrid model incorporates aspects from analytical performance modeling and machine learning, with the goal to combine their respective strengths. We show the applicability of our prediction model for two different use cases: (1) to dynamically steer the sampling density in object and/or image space and (2) to dynamically distribute the workload among several different parallel computing devices. Our approach allows to reliably meet performance requirements such as a user-defined frame rate, even in the case of sudden large changes to the transfer function or the camera orientation."
featured: false
publication: "*Visual Informatics*"
url_pdf: "https://doi.org/10.1016/j.visinf.2017.09.001"
doi: "10.1016/j.visinf.2017.09.001"

image:
  caption: Prediction-based multi-GPU load balancing for volume raycasting.
  focal_point: ""
  preview_only: false
---

