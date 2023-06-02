---
layout: post
category: blog1
title: 'My first post'
date: 2012-04-06 21:35
---

## Comparing models of neural representation based on their metric tensors

* We generalize a previous method (“eigendistortions” - Berardino et al, 2017) to compare neural/neural network models based on their metric tensors. Metric tensors characterize a model’s sensitivity to stimulus perturbations, reflecting both the geometric and stochastic properties of the representation, and providing an explicit prediction of perceptual discriminability. 

* Brute force comparison of model-predicted metric tensors using human perceptual thresholds would require an impossibly large set of measurements. To circumvent this “perceptual curse of dimensionality”, we compute and measure discrimination capabilities for a small set of most-informative perturbations, reducing the measurement cost from thousands of hours (a conservative estimate) to a single trial. 

* We demonstrate the power of this method in assessing three different examples: 1) comparing models for color discrimination; 2) comparing dense neural networks with different regularizers; 3) comparing adversarially-trained versus pre-trained neural networks for perceptual discriminability
