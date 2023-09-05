---
title: "Multi-center anatomical segmentation with heterogeneous labels via landmark-based models"
collection: publications
permalink: /publication/multicenter
excerpt: ''
date: 2023-09-01
status: 'Published at the 20th IEEE International Symposium on Biomedical Imaging (ISBI 2023)'
paperurl: 'https://arxiv.org/abs/2211.07395'
citation: 'N. Gaggion, M. Vaikalopoulou, D. H. Milone and E. Ferrante, "Multi-Center Anatomical Segmentation with Heterogeneous Labels Via Landmark-Based Models," 2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI), Cartagena, Colombia, 2023, pp. 1-5, doi: 10.1109/ISBI53787.2023.10230691.'
image: '/images/multicenter.png'
---

## Multi-center anatomical segmentation with heterogeneous labels via landmark-based models

<img src='/images/multicenter.png'>

### Abstract

Learning anatomical segmentation from heterogeneous labels in multi-center datasets is a common situation encountered in clinical scenarios, where certain anatomical structures are only annotated in images coming from particular medical centers, but not in the full database. Here we first show how state-of-the-art pixel-level segmentation models fail in naively learning this task due to domain memorization issues and conflicting labels. We then propose to adopt HybridGNet, a landmark-based segmentation model which learns the available anatomical structures using graph-based representations. By analyzing the latent space learned by both models, we show that HybridGNet naturally learns more domain-invariant feature representations, and provide empirical evidence in the context of chest X-ray multiclass segmentation. We hope these insights will shed light on the training of deep learning models with heterogeneous labels from public and multi-center datasets. 

### Citation
````
@INPROCEEDINGS{10230691,

  author={Gaggion, Nicol{\'a}s and Vaikalopoulou, Maria and Milone, Diego H. and Ferrante, Enzo},

  booktitle={2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI)}, 

  title={Multi-Center Anatomical Segmentation with Heterogeneous Labels Via Landmark-Based Models}, 

  year={2023},

  volume={},

  number={},

  pages={1-5},

  doi={10.1109/ISBI53787.2023.10230691}}
````
