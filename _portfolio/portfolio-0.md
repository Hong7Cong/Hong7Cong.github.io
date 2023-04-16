---
title: "Explaination AI for Image Classification Task under Transfer Learning Setting"
excerpt: "Can State-of-the-art (SOTA) algorithms understand images that are transfer-ed from different domain?"
collection: portfolio
---

We propose to create a explainable metric to evaluate explain-ability of the classification models
on fake objects that are generated from domain adaptation techniques. Given two dataset from
two different domain (for example, dog and cat datasets), we use CycleGAN to translate objects in
target domain to source domain. Simply speaking, we transform every dog images into cat images
using CycleGAN. The classification models (for example, vision transformer, Res-net) will then
apply on the fake image to classify. We keep tracking the realiability learning procedure by XAI,
more specifically, GradCAM, which visualized heat map of area of interest.

Our work simply answer a question: Can State-of-the-art (SOTA) algorithms understand images
that are transfer-ed from different domain?

[Proposal here](https://www.overleaf.com/read/qztqbrrrtfwp)


[Proposal here](https://www.overleaf.com/read/qztqbrrrtfwp)