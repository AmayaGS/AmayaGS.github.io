---
title: "Going Beyond H&E and Oncology: How Do Histopathology Foundation Models Perform for Multi-stain IHC and Immunology?"
collection: publications
permalink: /publication/2024-10-30-going-beyond-he
excerpt: 'Do histopathology Foundation Models trained on H&E cancer datasets enhance performance for Immunohistochemistry autoimmune datasets? Do they produce more relevant Whole Slide Image heatmaps, aligned with autoimmune aetiology? We empirically examine these questions in this paper.'
date: 2024-10-30
venue: 'Workshop on Advancements In Medical Foundation Models @ NeurIPS24'
paperurl: 'https://arxiv.org/abs/2410.21560'
citation: 'Amaya Gallagher-Syed, Elena Pontarini, Myles J. Lewis, Michael R. Barnes and Gregory Slabaugh, Going Beyond H&E and Oncology: How Do Histopathology Foundation Models Perform for Multi-stain IHC and Immunology?. Workshop on Advancements In Medical Foundation Models, NeurIPS 2024, Vancouver, Canada'
---

This study evaluates the generalisation capabilities of state-of-the-art histopathology foundation models on out-of-distribution multi-stain autoimmune Immunohistochemistry datasets. We compare 13 feature extractor models, including ImageNet-pretrained networks, and histopathology foundation models trained on both public and proprietary data, on Rheumatoid Arthritis subtyping and Sjogren's Disease detection tasks. Using a simple Attention-Based Multiple Instance Learning classifier, we assess the transferability of learned representations from cancer H&E images to autoimmune IHC images. Contrary to expectations, histopathology-pretrained models did not significantly outperform ImageNet-pretrained models. Furthermore, there was evidence of both autoimmune feature misinterpretation and biased feature importance. Our findings highlight the challenges in transferring knowledge from cancer to autoimmune histopathology and emphasise the need for careful evaluation of AI models across diverse histopathological tasks. 

[GitHub](https://github.com/AmayaGS/ImmunoHistoBench)

[Paper](https://arxiv.org/abs/2410.21560)

Bibtex citation:
```
@inproceedings{Gallagher-Syed_2024_AIM,
author    = {Amaya Gallagher-Syed and Elena Pontarini and Myles J. Lewis and Michael R. Barnes and Gregory Slabaugh},
title     = {Going Beyond H&E and Oncology: How Do Histopathology Foundation Models Perform for Multi-stain IHC and Immunology?},
booktitle = {Workshop on Advancements In Medical Foundation Models, NeurIPS 2024, Vancouver, Canada},
year      = {2024},
url       = {https://arxiv.org/abs/2410.21560}
}
```
