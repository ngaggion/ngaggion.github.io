---
title: "Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis"
collection: publications
permalink: /publication/hybridgnet_igsc
excerpt: 'Anatomical segmentation is a fundamental task in medical image computing, generally tackled with fully convolutional neural networks which produce dense segmentation masks. These models are often trained with loss functions such as cross-entropy or Dice, which assume pixels to be independent of each other, thus ignoring topological errors and anatomical inconsistencies. We address this limitation by moving from pixel-level to graph representations, which allow to naturally incorporate anatomical constraints by construction. To this end, we introduce HybridGNet, an encoder-decoder neural architecture that leverages standard convolutions for image feature encoding and graph convolutional neural networks (GCNNs) to decode plausible representations of anatomical structures. We also propose a novel image-to-graph skip connection layer which allows localized features to flow from standard convolutional blocks to GCNN blocks, and show that it improves segmentation accuracy. The proposed architecture is extensively evaluated in a variety of domain shift and image occlusion scenarios, and audited considering different types of demographic domain shift. Our comprehensive experimental setup compares HybridGNet with other landmark and pixel-based models for anatomical segmentation in chest x-ray images, and shows that it produces anatomically plausible results in challenging scenarios where other models tend to fail.'
date: 2022-03-19
venue: 'Arxiv pre-print'
paperurl: 'https://arxiv.org/abs/2203.10977'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

## Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis

### Abstract

Anatomical segmentation is a fundamental task in medical image computing, generally tackled with fully convolutional neural networks which produce dense segmentation masks. These models are often trained with loss functions such as cross-entropy or Dice, which assume pixels to be independent of each other, thus ignoring topological errors and anatomical inconsistencies. We address this limitation by moving from pixel-level to graph representations, which allow to naturally incorporate anatomical constraints by construction. To this end, we introduce HybridGNet, an encoder-decoder neural architecture that leverages standard convolutions for image feature encoding and graph convolutional neural networks (GCNNs) to decode plausible representations of anatomical structures. We also propose a novel image-to-graph skip connection layer which allows localized features to flow from standard convolutional blocks to GCNN blocks, and show that it improves segmentation accuracy. The proposed architecture is extensively evaluated in a variety of domain shift and image occlusion scenarios, and audited considering different types of demographic domain shift. Our comprehensive experimental setup compares HybridGNet with other landmark and pixel-based models for anatomical segmentation in chest x-ray images, and shows that it produces anatomically plausible results in challenging scenarios where other models tend to fail.

### Citation
````
@misc{https://doi.org/10.48550/arxiv.2203.10977,
  doi = {10.48550/ARXIV.2203.10977},
  url = {https://arxiv.org/abs/2203.10977},
  author = {Gaggion, Nicolás and Mansilla, Lucas and Mosquera, Candelaria and Milone, Diego H. and Ferrante, Enzo},
  keywords = {Image and Video Processing (eess.IV), Computer Vision and Pattern Recognition (cs.CV)},
  title = {Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution 4.0 International}
}
````
