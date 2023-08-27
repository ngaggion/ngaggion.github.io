---
title: "CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images"
collection: publications
permalink: /publication/chexmask
excerpt: ''
date: 2023-07-06
status: 'In review'
paperurl: 'https://arxiv.org/abs/2307.03293'
citation: 'Gaggion, N., Mosquera, C., Mansilla, L., Aineseder, M., Milone, D. H., & Ferrante, E. (2023). CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images. arXiv preprint arXiv:2307.03293.'
image: '/images/histogram_CheXmask_blue.png'
---

## CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images

<a href="{{ https://physionet.org/content/chexmask-cxr-segmentation-data }}">Dataset Link</a>

<img src='/images/histogram_CheXmask_blue.png'>

### Abstract

The development of successful artificial intelligence models for chest X-ray analysis relies on large, diverse datasets with high-quality annotations. While several databases of chest X-ray images have been released, most include disease diagnosis labels but lack detailed pixel-level anatomical segmentation labels. To address this gap, we introduce an extensive chest X-ray multi-center segmentation dataset with uniform and fine-grain anatomical annotations for images coming from six well-known publicly available databases: CANDID-PTX, ChestX-ray8, Chexpert, MIMIC-CXR-JPG, Padchest, and VinDr-CXR, resulting in 676,803 segmentation masks. Our methodology utilizes the HybridGNet model to ensure consistent and high-quality segmentations across all datasets. Rigorous validation, including expert physician evaluation and automatic quality control, was conducted to validate the resulting masks. Additionally, we provide individualized quality indices per mask and an overall quality estimation per dataset. This dataset serves as a valuable resource for the broader scientific community, streamlining the development and assessment of innovative methodologies in chest X-ray analysis. 

### Citation
````
@misc{gaggion2023chexmask,
      title={CheXmask: a large-scale dataset of anatomical segmentation masks for multi-center chest x-ray images}, 
      author={Nicolás Gaggion and Candelaria Mosquera and Lucas Mansilla and Martina Aineseder and Diego H. Milone and Enzo Ferrante},
      year={2023},
      eprint={2307.03293},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
````
