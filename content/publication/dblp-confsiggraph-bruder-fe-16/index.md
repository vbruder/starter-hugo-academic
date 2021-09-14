---
title: "Real-time performance prediction and tuning for interactive volume raycasting"
date: 2016-01-01
authors: 
- admin
- "Steffen Frey"
- "Thomas Ertl"
publication_types: ["1"]
abstract: "We present an integrated approach for the real-time performance prediction and tuning of volume raycasting. The usage of empty space skipping and early ray termination, among others, can induce significant variations in performance when camera configuration and transfer functions are adjusted. For interactive exploration, this can result in various unpleasant effects like abruptly reduced responsiveness or jerky motions. To overcome those effects, we propose an integrated approach to accelerate the rendering and assess performance-relevant data on-the-fly, including a new technique to estimate the impact of early ray termination. On this basis, we introduce a hybrid model, to achieve accurate predictions with only minimal computational footprint. Our hybrid model incorporates both aspects from analytical performance modeling and machine learning, with the goal to combine their respective strengths. Using our model, we dynamically steer the sampling density along rays with our automatic tuning technique. This approach allows to reliably meet performance requirements like a fixed frame rate, even in the case of large sudden changes to the transfer function or the camera. We finally demonstrate the accuracy and utility of our approach by means of a variety of different volume data sets and interaction sequences."
featured: false
publication: "*SIGGRAPH ASIA 2016, Macao, December 5-8, 2016 - Symposium on Visualization*"
url_pdf: "https://doi.org/10.1145/3002151.3002156"
doi: "10.1145/3002151.3002156"

image:
  caption: Predictive quality adaption to keep a defined frame time target during interactive volume rendering.
  focal_point: ""
  preview_only: false
---

