---
title: "Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis"
collection: publications
permalink: /publication/hybridgnet_igsc
excerpt: ''
date: 2022-11-24
status: 'Published at IEEE Transactions in Medical Imaging'
paperurl: 'https://ieeexplore.ieee.org/document/9963582'
citation: 'N. Gaggion, L. Mansilla, C. Mosquera, D. H. Milone and E. Ferrante, "Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis," in IEEE Transactions on Medical Imaging, 2022, doi: 10.1109/TMI.2022.3224660.'
image: '/images/hybrid_journal.png'
---

## Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis

<img src='/images/hybrid_journal.png'>

### Abstract

Anatomical segmentation is a fundamental task in medical image computing, generally tackled with fully convolutional neural networks which produce dense segmentation masks. These models are often trained with loss functions such as cross-entropy or Dice, which assume pixels to be independent of each other, thus ignoring topological errors and anatomical inconsistencies. We address this limitation by moving from pixel-level to graph representations, which allow to naturally incorporate anatomical constraints by construction. To this end, we introduce HybridGNet, an encoder-decoder neural architecture that leverages standard convolutions for image feature encoding and graph convolutional neural networks (GCNNs) to decode plausible representations of anatomical structures. We also propose a novel image-to-graph skip connection layer which allows localized features to flow from standard convolutional blocks to GCNN blocks, and show that it improves segmentation accuracy. The proposed architecture is extensively evaluated in a variety of domain shift and image occlusion scenarios, and audited considering different types of demographic domain shift. Our comprehensive experimental setup compares HybridGNet with other landmark and pixel-based models for anatomical segmentation in chest x-ray images, and shows that it produces anatomically plausible results in challenging scenarios where other models tend to fail.

### Citation
````
@ARTICLE{9963582,
  author={Gaggion, Nicolás and Mansilla, Lucas and Mosquera, Candelaria and Milone, Diego H. and Ferrante, Enzo},
  journal={IEEE Transactions on Medical Imaging}, 
  title={Improving anatomical plausibility in medical image segmentation via hybrid graph neural networks: applications to chest x-ray analysis}, 
  year={2022},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TMI.2022.3224660}}

````
