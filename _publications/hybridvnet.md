---
title: "Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI"
collection: publications
permalink: /publication/hybridvnet
excerpt: ''
date: 2025-05-19
status: 'Accepted for publication at Medical Image Analysis'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S136184152500177X'
citation: 'Gaggion, N., Matheson, B. A., Xia, Y., Bonazzola, R., Ravikumar, N., Taylor, Z. A., Milone, D. H., Frangi, A. F., & Ferrante, E. (2025). Multi-view hybrid graph convolutional network for volume-to-mesh reconstruction in cardiovascular MRI. Medical Image Analysis, 103630.'
image: '/images/hybridvnet.png'
---

## Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI

<img src='/images/hybridvnet.png'>

### Abstract

Cardiovascular magnetic resonance imaging is emerging as a crucial tool to examine cardiac morphology and function. Essential to this endeavour are anatomical 3D surface and volumetric meshes derived from CMR images, which facilitate computational anatomy studies, biomarker discovery, and in-silico simulations. Traditional approaches typically follow complex multi-step pipelines, first segmenting images and then reconstructing meshes, making them time-consuming and prone to error propagation. In response, we introduce HybridVNet, a novel architecture for direct image-to-mesh extraction seamlessly integrating standard convolutional neural networks with graph convolutions, which we prove can efficiently handle surface and volumetric meshes by encoding them as graph structures. To further enhance accuracy, we propose a multi-view HybridVNet architecture which processes both long axis and short axis CMR, showing that it can increase the performance of cardiac MR mesh generation. Our model combines traditional convolutional networks with variational graph generative models, deep supervision and mesh-specific regularisation. Experiments on a comprehensive dataset from the UK Biobank confirm the potential of HybridVNet to significantly advance cardiac imaging and computational cardiology by efficiently generating high-fidelity meshes from CMR images. Multi-view HybridVNet outperforms the state-of-the-art, achieving improvements of up to ∼27% reduction in Mean Contour Distance (from 1.86 mm to 1.35 mm for the LV Myocardium), up to ∼18% improvement in Hausdorff distance (from 4.74 mm to 3.89 mm, for the LV Endocardium), and up to ∼8% in Dice Coefficient (from 0.78 to 0.84, for the LV Myocardium), highlighting its superior accuracy.

### Citation
````
@article{GAGGION2025103630,
title = {Multi-view hybrid graph convolutional network for volume-to-mesh reconstruction in cardiovascular MRI},
journal = {Medical Image Analysis},
pages = {103630},
year = {2025},
issn = {1361-8415},
doi = {https://doi.org/10.1016/j.media.2025.103630},
url = {https://www.sciencedirect.com/science/article/pii/S136184152500177X},
author = {\textbf{Nicolás Gaggion} and Benjamin A. Matheson and Yan Xia and Rodrigo Bonazzola and Nishant Ravikumar and Zeike A. Taylor and Diego H. Milone and Alejandro F. Frangi and Enzo Ferrante},
keywords = {Cardiac imaging, Geometric deep learning, Hybrid graph convolutional neural network, Volume-to-mesh},
abstract = {Cardiovascular magnetic resonance imaging is emerging as a crucial tool to examine cardiac morphology and function. Essential to this endeavour are anatomical 3D surface and volumetric meshes derived from CMR images, which facilitate computational anatomy studies, biomarker discovery, and in-silico simulations. Traditional approaches typically follow complex multi-step pipelines, first segmenting images and then reconstructing meshes, making them time-consuming and prone to error propagation. In response, we introduce HybridVNet, a novel architecture for direct image-to-mesh extraction seamlessly integrating standard convolutional neural networks with graph convolutions, which we prove can efficiently handle surface and volumetric meshes by encoding them as graph structures. To further enhance accuracy, we propose a multi-view HybridVNet architecture which processes both long axis and short axis CMR, showing that it can increase the performance of cardiac MR mesh generation. Our model combines traditional convolutional networks with variational graph generative models, deep supervision and mesh-specific regularisation. Experiments on a comprehensive dataset from the UK Biobank confirm the potential of HybridVNet to significantly advance cardiac imaging and computational cardiology by efficiently generating high-fidelity meshes from CMR images. Multi-view HybridVNet outperforms the state-of-the-art, achieving improvements of up to ∼27% reduction in Mean Contour Distance (from 1.86 mm to 1.35 mm for the LV Myocardium), up to ∼18% improvement in Hausdorff distance (from 4.74 mm to 3.89 mm, for the LV Endocardium), and up to ∼8% in Dice Coefficient (from 0.78 to 0.84, for the LV Myocardium), highlighting its superior accuracy.}
}
````
