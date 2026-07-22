---
layout: page
title: research
permalink: /research/
description: Explainable, biology-aligned machine learning across computational pathology and single-cell genomics.
nav: true
nav_order: 1
---

I work at the intersection of **machine learning** and **biology**, building models that are not only accurate but *interpretable in biological terms* — and interrogating what modern foundation models actually learn about the structure of living systems. My work spans immunology and cancer, and connects imaging, genomics and perturbation data.

Broadly, my research follows three threads.

---

### 1 · Explainable, biology-aligned computational pathology

Histopathology is central to diagnosis, but most deep-learning pipelines are black boxes trained on H&amp;E-stained cancer tissue. I develop **multi-stain, multimodal** models — built on graph neural networks and attention-based multiple-instance learning — that stay faithful to how pathologists and immunologists actually reason about tissue, and that reveal *which* biological structures drive a prediction.

- **BioX-CPath** — biologically-driven, explainable diagnostics for multistain IHC *(CVPR 2025)*
- **MUSTANG** — multi-stain self-attention graph MIL for whole-slide images *(BMVC 2023)*
- **ProtoPathway** — biologically structured prototype–pathway fusion for multimodal cancer survival prediction *(under review, 2026)*
- **Going Beyond H&amp;E and Oncology** — how histopathology foundation models transfer to multi-stain IHC and immunology *(NeurIPS 2024 workshop)*

### 2 · Probing &amp; benchmarking biological foundation models

Foundation models for single cells and tissue are advancing quickly, but it's often unclear what biological knowledge they encode — or whether they capture genuine regulatory structure. I build **mechanistic probes and rigorous benchmarks** to find out, using interventional data such as CRISPR Perturb-seq to test models against known biology.

- **CLAMP** — a mechanistic probe of regulatory structure in foundation models under single-cell perturbations *(ICML 2026 workshop, Spotlight)*
- **PertEval-scFM** — benchmarking single-cell foundation models for perturbation-effect prediction *(ICML 2025)*

### 3 · Toward mechanistic, virtual-cell models

My emerging direction — and the focus of my Schmidt AI for Science Fellowship at Imperial's I-X — is **identifiable representation learning and cross-modal causal discovery**: models whose latent structure is recoverable and meaningful, combining differentiable programming, dynamical systems and causal inference from interventional data, working toward mechanistic *virtual-cell* models that generalise across modalities.

---

### Clinical &amp; translational impact

This work is grounded in real clinical questions. In collaboration with clinicians and immunologists, we showed that machine learning can classify focus score and support diagnosis of **Sjögren's disease** directly from digitised salivary gland biopsies — published in *The Lancet Rheumatology* (2025).

For the full list of papers, see my [publications](/publications/) or [Google Scholar](https://scholar.google.com/citations?user=UYDwER0AAAAJ). Code is available on [GitHub](https://github.com/AmayaGS).
