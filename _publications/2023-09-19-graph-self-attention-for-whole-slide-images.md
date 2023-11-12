---
title: "MUSTANG: Multi-Stain Self-Attention Graph Multiple Instance Learning Pipeline for Histopathology Whole Slide Images"
collection: publications
permalink: /publication/2023-09-19-graph-self-attention-for-whole-slide-images
excerpt: 'Here we propose an end-to-end multi-stain self-attention graph (MUSTANG) multiple instance learning pipeline, which is designed to solve a weakly-supervised gigapixel multi-image classification task, where the label is assigned at the patient-level, but no slide-level labels or region annotations are available. The pipeline uses a self-attention based approach by restricting the operations to a highly sparse k-Nearest Neighbour Graph of embedded WSI patches based on the Euclidean distance.'
date: 2023-09-19
venue: 'British Machine Vision Conference'
paperurl: 'https://arxiv.org/abs/2309.10650.pdf'
citation: 'Gallagher-Syed, A., Rossi, L., Rivellese, F., Pitzalis, C., Lewis, M., Barnes, M. and Slabaugh, G., 2023. Multi-Stain Self-Attention Graph Multiple Instance Learning Pipeline for Histopathology Whole Slide Images. arXiv preprint arXiv:2309.10650.'
---

Whole Slide Images (WSIs) present a challenging computer vision task due to their gigapixel size and presence of numerous artefacts. Yet they are a valuable resource for patient diagnosis and stratification, often representing the gold standard for diagnostic tasks. Real-world clinical datasets tend to come as sets of heterogeneous WSIs with labels present at the patient-level, with poor to no annotations. Weakly supervised attention-based multiple instance learning approaches have been developed in recent years to address these challenges, but can fail to resolve both long and short-range dependencies. Here we propose an end-to-end multi-stain self-attention graph (MUSTANG) multiple instance learning pipeline, which is designed to solve a weakly-supervised gigapixel multi-image classification task, where the label is assigned at the patient-level, but no slide-level labels or region annotations are available. The pipeline uses a self-attention based approach by restricting the operations to a highly sparse k-Nearest Neighbour Graph of embedded WSI patches based on the Euclidean distance. We show this approach achieves a state-of-the-art F1-score/AUC of 0.89/0.92, outperforming the widely used CLAM model. Our approach is highly modular and can easily be modified to suit different clinical datasets, as it only requires a patient-level label without annotations and accepts WSI sets of different sizes, as the graphs can be of varying sizes and structures. 

GitHub repo: https://github.com/AmayaGS/MUSTANG

Bibtex citation:
```
@misc{gallaghersyed2023mustang,
      title={MUSTANG: Multi-Stain Self-Attention Graph Multiple Instance Learning Pipeline for Histopathology Whole Slide Images}, 
      author={Amaya Gallagher-Syed and Luca Rossi and Felice Rivellese and Costantino Pitzalis and Myles Lewis and Michael Barnes and Gregory Slabaugh},
      year={2023},
      eprint={2309.10650},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
