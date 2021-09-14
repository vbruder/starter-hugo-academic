---
title: "Prediction of Distributed Volume Visualization Performance to Support Render Hardware Acquisition"
date: 2017-01-01
authors: 
- "Gleb Tkachev"
- "Steffen Frey"
- "Christoph Müller"
- admin
- "Thomas Ertl"
publication_types: ["1"]
abstract: "We present our data-driven, neural network-based approach to predicting the performance of a distributed GPU volume renderer for supporting cluster equipment acquisition. On the basis of timing measurements from a single cluster as well as from individual GPUs, we are able to predict the performance gain of upgrading an existing cluster with additional or faster GPUs, or even purchasing of a new cluster with a comparable network configuration. To achieve this, we employ neural networks to capture complex performance characteristics. However, merely relying on them for the prediction would require the collection of training data on multiple clusters with different hardware, which is impractical in most cases. Therefore, we propose a two-level approach to prediction, distinguishing between node and cluster level. On the node level, we generate performance histograms on individual nodes to capture local rendering performance. These performance histograms are then used to emulate the performance of different rendering hardware for cluster-level measurement runs. Crucially, this variety allows the neural network to capture the compositing performance of a cluster separately from the rendering performance on individual nodes. Therefore, we just need a performance histogram of the GPU of interest to generate a prediction. We demonstrate the utility of our approach using different cluster configurations as well as a range of image and volume resolutions."
featured: false
publication: "*EGPGV17: Eurographics Symposium on Parallel Graphics and Visualization, Barcelona, Spain, June 12-13, 2017*"
publication_short: "*EGPGV17*"
url_pdf: "https://doi.org/10.2312/pgv.20171089"
doi: "10.2312/pgv.20171089"

image:
  caption: Volume rendering performance prediction on a cluster.
  focal_point: Smart
  preview_only: false
---

