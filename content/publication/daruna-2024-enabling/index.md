---
title: 'Enabling Scalable Mineral Exploration: Self-Supervision and Explainability'
authors:
- Angel Daruna
- Vasily Zadorozhnyy
- Georgina Lukoczki
- Han-Pang Chiu
date: '2024-01-01'
publishDate: '2025-05-19T02:16:08.233041Z'
publication_types:
- paper-conference
publication: '*2024 IEEE International Conference on Big Data (BigData)*'
abstract: Machine Learning (ML) for Mineral Prospectivity Mapping (MPM) is important for automating and accelerating the workflow to critical mineral assessment. Recent MPM works have explored Deep Learning (DL) as a modeling tool with more representation capacity. However, these overparameterized methods may be more prone to overfitting due to their reliance on scarce labeled data which is naturally inherent in mineral-relevant data sources. DL predictions can also be challenging to be interpreted and validated from a geological perspective to industrial experts. We propose a new unified framework that addresses these DL difficulties for MPM, using self-supervised learning, explainable artificial intelligence, and epistemic uncertainty modeling. Our approach uses a masked image modeling framework to pretrain a backbone neural network in a self-supervised manner using unlabeled geospatial data alone. After pretraining, the backbone network provides feature extraction for downstream MPM tasks. We conducted rigorous evaluations against existing techniques to assess mineral prospectivity for Mississippi Valley-type (MVT) and Clastic-Dominated (CD) Zn–Pb deposits in North America and Australia. Our results demonstrate that self-supervision promotes robustness in learned features, improving prospectivity predictions. Furthermore, we incorporate and demonstrate how explainable artificial intelligence techniques can provide interpretable predictions, offering valuable geological insights for industry professionals involved in high-stakes resource exploration and development.

summary: This work introduces a unified framework for Mineral Prospectivity Mapping that combines self-supervised learning, explainable AI, and uncertainty modeling to overcome challenges in deep learning caused by limited labeled data and interpretability. The approach improves prediction robustness and provides geologically meaningful insights, demonstrated through evaluations on Zn–Pb deposits in North America and Australia.

tags:
- Self-Supervised Learning

featured: true

image:
  caption: 'Architecture Overview'
  focal_point: ''
  preview_only: false
---
