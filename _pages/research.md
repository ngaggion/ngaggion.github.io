---
permalink: /research
title: "Research Lines"
excerpt: ""
author_profile: true
---

I work mainly on two different research lines:

- **Plant root phenotyping using deep learning**:\
  My Computing Engineer thesis consisted on the development of a deep learning based approach to provide high throughtput phenotyping of plant roots in temporal series of images using deep learning. This project was done in colaboration with my co-supervisor Federico Ariel from the [Instituto de Agrobiotecnología del Litoral](https://ial.conicet.gov.ar/) (IAL), and members of the [Institute of Plant Sciences Paris Saclay](https://ips2.u-psud.fr/en/index.html) (IPS2).\
  We are currently putting this work into production, in order to be used at several plant biology labs around the globe. \
  Within this project, we also launched a [root segmentation challenge](https://sites.google.com/sinc.unl.edu.ar/root-segmentation-challenge) during the CVPPA workshop at ICCV '21. 

- **Image-to-graph extraction mixing graph neural networks with convolutional neural networks:**\
  As the main topic of my PhD thesis, I am currently working on the image-to-graph extraction problem in the context of medical imaging. In particular, I'm applying this approach to segment images using graph representations of the anatomical structure (such as meshes) instead of providing pixel-level segmentations. \
  During July 2022, I made a research visit to the [Center for Computational Imaging & Simulation Technologies in Biomedicine, CISTIB](https://www.cistib.org/), under the supervision of Prof. Alex Frangi. There we began our collaboration to perform automatic mesh extraction from cardiac MRI images, on UK Biobank data.

Both research lines coincide in the problem of extracting graph structures from images. On the first one, we obtain a graph representation of the plant root by a mix of deep learning based segmentation and a classic approach of graph construction from the segmentation's skeleton. On the second one, we produce end-to-end trainable models for anatomical segmentation via graph neural networks.
