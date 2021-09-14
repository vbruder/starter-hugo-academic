---
title: "Adaptive Encoder Settings for Interactive Remote Visualisation on High-Resolution Displays"
date: 2018-01-01
authors: ["Florian Frieß", "Mathias Landwehr", "Valentin Bruder", "Steffen Frey", "Thomas Ertl"]
publication_types: ["1"]
abstract: "We present an approach that dynamically adapts encoder settings for image tiles to yield the best possible quality for a given bandwidth. This reduces the overall size of the image while preserving details. Our application determines the encoding settings in two steps. In the first step, we predict the quality and size of the tiles for different encoding settings using a convolutional neural network. In the second step, we assign the optimal encoder setting to each tile, so that the overall size of the image is lower than a predetermined threshold. Commonly, for tiles that contain complicated structures, a high quality setting is used in order to prevent major information loss, while quality settings are lowered for others to keep the size below the threshold. We demonstrate that we can reduce the overall size of the image while preserving the details in areas of interest using the example of both particle and volume visualization applications."
featured: false
publication: "*8th IEEE Symposium on Large Data Analysis and Visualization, LDAV 2018, Berlin, Germany, October 21, 2018*"
url_pdf: "https://doi.org/10.1109/LDAV.2018.8739215"
doi: "10.1109/LDAV.2018.8739215"

image:
  caption: Different encoding strategies per tile based on quality and size predictions.
  focal_point: Smart
  preview_only: false
---

