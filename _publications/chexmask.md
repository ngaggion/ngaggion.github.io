---
title: "CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images"
collection: publications
permalink: /publication/chexmask
excerpt: ''
date: 2024-05-05
status: 'Published in Nature Scientific Data'
paperurl: 'https://doi.org/10.1038/s41597-024-03358-1'
citation: 'Gaggion, N., Mosquera, C., Mansilla, L., Saidman, J. M., Aineseder, M., Milone, D. H., & Ferrante, E. (2024). CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images. Scientific Data, 11(1), 511.'
image: '/images/histogram_CheXmask_blue.png'
dataset_link: 'https://physionet.org/content/chexmask-cxr-segmentation-data'
---

## CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images

<img src='/images/histogram_CheXmask_blue.png'>

### Abstract

The development of successful artificial intelligence models for chest X-ray analysis relies on large, diverse datasets with high-quality annotations. While several databases of chest X-ray images have been released, most include disease diagnosis labels but lack detailed pixel-level anatomical segmentation labels. To address this gap, we introduce an extensive chest X-ray multi-center segmentation dataset with uniform and fine-grain anatomical annotations for images coming from six well-known publicly available databases: CANDID-PTX, ChestX-ray8, Chexpert, MIMIC-CXR-JPG, Padchest, and VinDr-CXR, resulting in 676,803 segmentation masks. Our methodology utilizes the HybridGNet model to ensure consistent and high-quality segmentations across all datasets. Rigorous validation, including expert physician evaluation and automatic quality control, was conducted to validate the resulting masks. Additionally, we provide individualized quality indices per mask and an overall quality estimation per dataset. This dataset serves as a valuable resource for the broader scientific community, streamlining the development and assessment of innovative methodologies in chest X-ray analysis. 

### Citation
````
@Article{gaggion2024chexmask,
  author   = {Gaggion, Nicolás and Mosquera, Candelaria and Mansilla, Lucas and Saidman, Julia Mariel and Aineseder, Martina and Milone, Diego H. and Ferrante, Enzo},
  title    = {CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images},
  doi      = {10.1038/s41597-024-03358-1},
  issn     = {2052-4463},
  number   = {1},
  pages    = {511},
  url      = {https://doi.org/10.1038/s41597-024-03358-1},
  volume   = {11},
  journal  = {Scientific Data},
  refid    = {Gaggion2024},
  year     = {2024},
}
````
