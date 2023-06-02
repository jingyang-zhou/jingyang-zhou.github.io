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

* da Fonseca and Samengo (2016) used a neural model combined with Fisher information (a quantification of perceptual thresholds) to predict the pattern of chromatic thresholds measured in human observers. The model assumes linear cone responses paired with Poisson noise. I furthered the analysis, and studied two additional aspects of chromatic perception.

* First, I quantified how the pattern of chromatic thresholds vary when the proportion of three cone types (short-, mid-, and long-wavelength) varies. This analysis potentially leads to efficient estimation of chromatic thresholds. Second, I analyzed to what extent the assumption of Poisson noise contributes to the threshold predictions. 
Surprisingly, eliminating Poisson noise betters the model prediction. So in addition to Poisson noise, I examined three other types of noise assumptions, and achieved improved predictions to MacAdam's data.

* Last, I showed an application using model-predicted chromatic thresholds. The total number of cones, and the proportion of $S$ cone vary across retinal eccentricities. 
I examined how these variations predict drastically different chromatic threshold patterns across retinal eccentricities. 


## How does perceptual discriminability relate to neuronal receptive fields?

* Our perception changes only when underlying neuronal responses change. Because visual neurons preferentially respond to some pixel adjustments in an image, perceptually we are more sensitive to change in some pixel combinations more than others. 

* We examined how perceptual discriminability varies to arbitrary image perturbations assuming canonical models of neuronal responses. In particular, we assume discriminability reflects the magnitude of change (L2 norm) in neuronal responses, and we examined how perceptual discrim- inability relates to deterministic and stochastic neuronal computations. 
