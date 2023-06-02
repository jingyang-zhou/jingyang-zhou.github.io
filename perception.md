---
layout: post
title: Perception
---

## Comparing models of neural representation based on their metric tensors

* We compare neural/neural network models based on their metric tensors. Metric tensors characterize a model’s sensitivity to stimulus perturbations, reflecting both the geometric and stochastic properties of the representation, and providing an explicit prediction of perceptual discriminability. 

* Brute force comparison of model-predicted metric tensors using human perceptual thresholds require an impossibly large set of measurements. To circumvent this “perceptual curse of dimensionality”, we compute and measure discrimination capabilities for a small set of most-informative perturbations, reducing the measurement cost from thousands of hours (a conservative estimate) to a single trial. 

* We demonstrate the power of this method in assessing three different examples: 1) comparing models for color discrimination; 2) comparing dense neural networks with different regularizers; 3) comparing adversarially-trained versus pre-trained neural networks for perceptual discriminability.


## A common framework for discriminability and perceived intensity of sensory stimuli

* The perception of sensory attributes is often quantified through measurements of discriminability (an observers' ability to detect small changes in stimulus), as well as direct judgements of appearance or intensity. Despite their ubiquity, the relationship between these two measurements is controversial and unresolved. 

* We propose a framework in which both measurements arise from the properties of a common internal representation. Specifically, we assume that direct measurements of stimulus intensity (e.g., through rating scales) reflect the mean value of an internal representation, whereas measurements of discriminability reflect the ratio of the derivative of mean value to the internal noise amplitude, as captured by the measure of Fisher Information. 

* Combination of the two measurements allows unique identification of internal representation properties. As a central example, we show that Weber's Law of perceptual discriminability can co-exist with Stevens' observations of power-law scaling of perceptual intensity ratings (for all exponents), if one assumes an internal representation with noise amplitude proportional to the mean. 

* We extend this result by incorporating a more general physiology-inspired model for noise and a discrimination form that extends beyond Weber's range, and show that the combination allows accurate prediction of intensity ratings across a variety of sensory modalities and attributes. Our framework unifies two major perceptual measurements, and provides a potential neural interpretation for the underlying representations.

## Quantifying and predicting chromatic thresholds

## How does perceptual discriminability relate ot neuronal receptive fields?
