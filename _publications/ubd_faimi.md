---
title: "Unsupervised bias discovery in medical image segmentation"
collection: publications
permalink: /publication/ubd_faimi
excerpt: ''
date: 2023-11-02
status: 'Published at Fairness of AI in Medical Imaging - MICCAI 2023 Workshop'
paperurl: 'https://arxiv.org/abs/2309.00451'
citation: 'Gaggion, N., Echeveste, R., Mansilla, L., Milone, D. H., & Ferrante, E. (2023, October). Unsupervised bias discovery in medical image segmentation. In Workshop on Clinical Image-Based Procedures (pp. 266-275). Cham: Springer Nature Switzerland.'
image: '/images/ubd_faimi.png'
---

## Unsupervised bias discovery in medical image segmentation

<img src='/images/ubd_faimi.png'>

### Abstract

It has recently been shown that deep learning models for anatomical segmentation in medical images can exhibit biases against certain sub-populations defined in terms of protected attributes like sex or ethnicity. In this context, auditing fairness of deep segmentation models becomes crucial. However, such audit process generally requires access to ground-truth segmentation masks for the target population, which may not always be available, especially when going from development to deployment. Here we propose a new method to anticipate model biases in biomedical image segmentation in the absence of ground-truth annotations. Our unsupervised bias discovery method leverages the reverse classification accuracy framework to estimate segmentation quality. Through numerical experiments in synthetic and realistic scenarios we show how our method is able to successfully anticipate fairness issues in the absence of ground-truth labels, constituting a novel and valuable tool in this field. 

### Citation
````
@inproceedings{gaggion2023unsupervised,
  title={Unsupervised bias discovery in medical image segmentation},
  author={Gaggion, Nicol{\'a}s and Echeveste, Rodrigo and Mansilla, Lucas and Milone, Diego H and Ferrante, Enzo},
  booktitle={Workshop on Clinical Image-Based Procedures},
  pages={266--275},
  year={2023},
  organization={Springer}
}
````
