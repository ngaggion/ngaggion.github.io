---
title: "Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI"
collection: publications
permalink: /publication/hybridvnet
excerpt: ''
date: 2023-11-22
status: 'In review'
paperurl: 'https://arxiv.org/abs/2311.13706'
citation: 'Gaggion, N., Matheson, B. A., Xia, Y., Bonazzola, R., Ravikumar, N., Taylor, Z. A., ... & Ferrante, E. (2023). Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI. arXiv preprint arXiv:2311.13706.'
image: '/images/hybridvnet.png'
---

## Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI

<img src='/images/hybridvnet.png'>

### Abstract

Cardiovascular magnetic resonance imaging is emerging as a crucial tool to examine cardiac morphology and function. Essential to this endeavour are anatomical 3D surface and volumetric meshes derived from CMR images, which facilitate computational anatomy studies, biomarker discovery, and in-silico simulations. However, conventional surface mesh generation methods, such as active shape models and multi-atlas segmentation, are highly time-consuming and require complex processing pipelines to generate simulation-ready 3D meshes. In response, we introduce HybridVNet, a novel architecture for direct image-to-mesh extraction seamlessly integrating standard convolutional neural networks with graph convolutions, which we prove can efficiently handle surface and volumetric meshes by encoding them as graph structures. To further enhance accuracy, we propose a multiview HybridVNet architecture which processes both long axis and short axis CMR, showing that it can increase the performance of cardiac MR mesh generation. Our model combines traditional convolutional networks with variational graph generative models, deep supervision and mesh-specific regularisation. Experiments on a comprehensive dataset from the UK Biobank confirm the potential of HybridVNet to significantly advance cardiac imaging and computational cardiology by efficiently generating high-fidelity and simulation ready meshes from CMR images. 

### Citation
````
@misc{gaggion2023multiview,
      title={Multi-view Hybrid Graph Convolutional Network for Volume-to-mesh Reconstruction in Cardiovascular MRI}, 
      author={Nicolás Gaggion and Benjamin A. Matheson and Yan Xia and Rodrigo Bonazzola and Nishant Ravikumar and Zeike A. Taylor and Diego H. Milone and Alejandro F. Frangi and Enzo Ferrante},
      year={2023},
      eprint={2311.13706},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
````
