---
layout: post
title: Neuroscience
---

## Representational dissimilarity metric spaces for stochastic neural networks

* Existing methods compare deterministic responses (e.g. artificial networks that lack stochastic layers) or averaged responses (e.g., trial-averaged firing rates in biological data). However, these measures of deterministic representational similarity ignore the scale and geometric structure of noise, both of which play important roles in neural computation. 

* We generalize previously proposed shape metrics (Williams et al., 2021) to quantify differences in stochastic representations. These new distances satisfy the triangle inequality, and thus can be used as a rigorous basis for many supervised and unsupervised analyses. 

* We find that the stochastic geometries of neurobiological representations of oriented visual gratings and naturalistic scenes respectively resemble untrained and trained deep network representations. Further, we are able to more accurately predict certain network attributes (e.g. training hyperparameters) from its position in stochastic (versus deterministic) shape space.


## Delayed normalization model captures disparate nonlinear neural dynamics measured with different techniques in macaque and human V1

* Voltage-sensitive dye imaging (VSDI) is a powerful method for measuring neural population responses from the cortex of awake, behaving, subjects. We used VSDI to measure the
dynamics of neural population responses in macaque V1 to visual stimuli with a wide range of time courses. We built a simple yet flexible delayed normalization model to capture the dynamics of all these measurements.

* We found that beyond clear nonlinearities for briefly presented visual stimuli, stimulus-evoked VSDI responses are near additive in time, which qualitatively differs from neural dynamics previously measured in human visual cortex using fMRI and electrocorticography (ECoG), which show strong sub-additivity in time.

* To test whether this discrepancy is specific to VSDI, a signal dominated by subthreshold neural activity, we repeated our measurements using a genetically encoded calcium indicator (GCaMP), a signal dominated by spiking activity. We found that GCaMP signals in macaque V1 are also near additive. 



## Predicting neuronal dynamics with a delayed gain control model

* Visual neurons respond to static images with specific dynamics: neuronal responses sum sub-additively over time, reduce in amplitude with repeated or sustained stimuli (neuronal adaptation), and are slower at low stimulus contrast. 

* We propose a simple delayed normalization model that predicts these seemingly disparate response patterns observed in a diverse set of measurements–intracranial electrodes in patients, fMRI, and macaque single unit spiking. 

* Fitting the model to intracranial EEG data uncovers two regularities across human visual field maps: estimated linear filters (temporal receptive fields) systematically differ across and within visual field maps, and later areas exhibit more rapid and substantial gain control. The model is further generalizable to account for dynamics of contrast-dependent spike rates in macaque V1, and amplitudes of fMRI BOLD in human V1.


## Systematic changes in temporal summation across human visual cortex

* How visual areas in the human brain process information distributed over time? One challenge to answer this question is that the most widely used neuroimaging method, fMRI, has coarse temporal resolution compared with the time-scale of neural dynamics. 

* Via carefully controlled temporally modulated stimuli, we show that information about temporal processing can be readily derived from fMRI signal amplitudes. We find that all visual areas exhibit subadditive summation, whereby responses to longer stimuli are less than the linear prediction from briefer stimuli. We also find fMRI evidence that the neural response to two stimuli is reduced for brief interstimulus intervals (indicating adaptation). These effects are more pronounced in visual areas anterior to V1-V3. 

* We develop a general model that shows how these effects can be captured with two simple operations: temporal summation followed by a compressive nonlinearity. This model operates for arbitrary temporal stimulation patterns and provides a simple and interpretable set of computations that can be used to characterize neural response properties across the visual hierarchy. 
