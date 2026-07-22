---
layout: page
title: Research
permalink: /research/
description: Identifiability and causality in biological systems, and the foundation models we use to study them.
nav: true
nav_order: 1
---

I work at the intersection of **machine learning** and **biology**. My central question is how to learn representations of biological systems that are *identifiable* and *causal*: models whose internal structure reflects real biology, that we can train and evaluate rigorously, and that transfer across data modalities.

My research follows three threads.

---

### 1 · Identifiability and causality in biological systems

This is the focus of my Schmidt AI for Science Fellowship at Imperial's I-X, and the direction I am building my research programme around. I work on **identifiable representation learning** and **cross-modal causal discovery**: combining differentiable programming, dynamical systems and causal inference from interventional data, working toward mechanistic *virtual-cell* models that generalise across genomics, imaging and perturbation data.

### 2 · Probing and benchmarking biological foundation models

Foundation models for single cells and tissue are advancing quickly, but it is often unclear what biological knowledge they encode, or whether they capture genuine regulatory structure. I build **mechanistic probes and rigorous benchmarks** to find out, using interventional data such as CRISPR Perturb-seq to test models against known biology.

- **CLAMP**: a mechanistic probe of regulatory structure in foundation models under single-cell perturbations *(ICML 2026 workshop, Spotlight)*
- **PertEval-scFM**: benchmarking single-cell foundation models for perturbation-effect prediction *(ICML 2025)*

### 3 · Explainable computational pathology

This was the focus of my PhD: **multi-stain, multimodal deep learning** for computational pathology in immunology and cancer, built on graph neural networks and attention-based multiple-instance learning, and designed to stay faithful to how pathologists and immunologists reason about tissue. I still do some work in this space, particularly on gene regulatory networks and spatial transcriptomics.

- **ProtoPathway**: biologically structured prototype–pathway fusion for multimodal cancer survival prediction *(under review, 2026)*
- **BioX-CPath**: biologically-driven, explainable diagnostics for multistain IHC *(CVPR 2025)*
- **MUSTANG**: multi-stain self-attention graph MIL for whole-slide images *(BMVC 2023)*

This work is grounded in real clinical questions. With clinicians and immunologists, we showed that machine learning can classify focus score and support diagnosis of **Sjögren's disease** directly from digitised salivary gland biopsies, published in *The Lancet Rheumatology* (2025).

---

For the full list of papers, see my [publications](/publications/) or [Google Scholar](https://scholar.google.com/citations?user=UYDwER0AAAAJ). Code is on [GitHub](https://github.com/AmayaGS).
