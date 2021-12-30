---
title: Current Projects
nav: Current Projects
description: >
    This page has information on my current projects.
---

## Tensor Feature Reduction
As part of the [Biomedical and Clinical Informatics Lab](https://najarianlab.ccmb.med.umich.edu/home) I am working on a tensor based feature space reduction method. The goal is to represent multiple signals recorded in time and space as a single tensor and to apply tensor decomposition methods (primarily CANDECOMP and Higher Order SVD) to extract features that are representative of the original wave form signals. The extracted features are used to train classification models, and the performance of these models is compared relative to the vectorization of the tensors. This work extends the previous results from [Multimodal tensor-based method for integrative and continuous patient monitoring during postoperative cardiac care](https://www.sciencedirect.com/science/article/pii/S0933365721000257) by applying a similar algorithm to wave form signals collected from EEG, ECG, and machine fault detection data, all of which is publicly available.

## In-Vehicle Cardiac Monitoring
A significan number of traffic accidents are caused by medical conditions while driving, and this issue is expected to worsen as the population ages. Sponsored by Toyota, the [Biomedical and Clinical Informatics Lab](https://najarianlab.ccmb.med.umich.edu/home) is developing an in vehicle cardiac monitoring system, designed to detect cardiac events prior to the driver becoming impared. 

## VRE Transmission Models
Vancomycin Resistant Enterococcus (VRE) is an antibiotic ressitant bacteria commonly found at in patient health settings. Working with the [King](https://kinglab.eeb.lsa.umich.edu/) and [Woods](https://the-woods-lab.com/) Labs, I have been developing models to simulate in patient movement patters at Michigan Medicine. The simulation models are multiorder Markov models based on the paper [Selective Markov Models for Predicting Web-Page Accesses](https://archive.siam.org/meetings/sdm01/pdf/sdm01_04.pdf). These models are built based on a decade of patient data, and they are the basis for simulating coupled disease transmission models using estimated parameters for VRE transmission. The purpose of studying the movement patterns is to provide insight into the hospital population, which is structured in space and patient comorbidities. The simulation algorithm is based off of the [Gillespie Direct Method](https://www.sciencedirect.com/science/article/pii/0021999176900413). This work is part of a larger project by the group studying VRE tranmission at Michigan Medicine.
