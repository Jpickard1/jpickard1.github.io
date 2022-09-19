---
title: Previous Projects
nav: Previous Projects
description: >
    The page contains information about previous projects I have worked on
---

## VRE Transmission Models
Vancomycin Resistant Enterococcus (VRE) is an antibiotic ressitant bacteria commonly found at in patient health settings. Working with the [King](https://kinglab.eeb.lsa.umich.edu/) and [Woods](https://the-woods-lab.com/) Labs, I have been developing models to simulate in patient movement patters at Michigan Medicine. The simulation models are multiorder Markov models based on the paper [Selective Markov Models for Predicting Web-Page Accesses](https://archive.siam.org/meetings/sdm01/pdf/sdm01_04.pdf). These models are built based on a decade of patient data, and they are the basis for simulating coupled disease transmission models using estimated parameters for VRE transmission. The purpose of studying the movement patterns is to provide insight into the hospital population, which is structured in space and patient comorbidities. The simulation algorithm is based off of the [Gillespie Direct Method](https://www.sciencedirect.com/science/article/pii/0021999176900413). This work is part of a larger project by the group studying VRE tranmission at Michigan Medicine.

## Tensor Feature Reduction
As part of the [Biomedical and Clinical Informatics Lab](https://najarianlab.ccmb.med.umich.edu/home) I am working on a tensor based feature space reduction method. The goal is to represent multiple signals recorded in time and space as a single tensor and to apply tensor decomposition methods (primarily CANDECOMP and Higher Order SVD) to extract features that are representative of the original wave form signals. The extracted features are used to train classification models, and the performance of these models is compared relative to the vectorization of the tensors. This work extends the previous results from [Multimodal tensor-based method for integrative and continuous patient monitoring during postoperative cardiac care](https://www.sciencedirect.com/science/article/pii/S0933365721000257) by applying a similar algorithm to wave form signals collected from EEG, ECG, and machine fault detection data, all of which is publicly available. A journal article is currently in preparation based on the results of this project.

## In-Vehicle Cardiac Monitoring
A significan number of traffic accidents are caused by medical conditions while driving, and this issue is expected to worsen as the population ages. Working with Toyota, the [Biomedical and Clinical Informatics Lab](https://najarianlab.ccmb.med.umich.edu/home) is developing an in vehicle cardiac monitoring system, designed to detect cardiac events prior to the driver becoming impared. This involves designing a custom sensing unit for a car seat and developing new algorithms capable accepting multiple simultaneously recorded signals with varrying amounts of noise. This is an ongoing project that I joined in the fall of 2020, and the most recent publication related to the methodology used in this project can be fount [here](https://www.sciencedirect.com/science/article/pii/S1746809420303347). A book chapter is currently in preparation based on the results of this project.

## [Michigan Institute of Data Science Bootcamp](https://jpickard1.github.io/content/previous_projects/MIDAS.html)

During the summers of 2021 and 2022, I was an instructor for the [Data Science for Biomedical Scientist](https://midas.umich.edu/data-science-for-biomedical-scientists/) workshop. This one week course covered the fundamentals of data science and introductory machine learning. I developed and taught programming lectures that applied different algorithms to biological and clinical data. My code and the data used are available in google colab notebooks.

## [Intelligent Fault Detection with Ball Bearings](https://jpickard1.github.io/content/previous_projects/Ball_Bearings_and_Vibration_Images.pdf)

This project explored and recreated the results in the paper [Rolling Element Bearing Fault Diagnosis Using Convolutional Neural Network and Vibration Image](https://www.sciencedirect.com/science/article/abs/pii/S1389041717303261).

## [Machine Learning Notes](https://drive.google.com/file/d/1-IX-_AwHDNvIuR2fkbN5uYLO6sQLxs2J/view?usp=sharing)

During my time at the University of Michigan, I have been complining a set of notes covering my favorite topics in machine learning, signals processing, and other related topics. This document initially began when I took Signals Processing and Machine Learning for Biomedical Sciences and Introduction to Machine Learning in the winter of 2021, and it has grown to include additional material as well. I recently went through adding new sections to the document in the Fall of 2021. I am not currently editing this document, but I plan to continue growing it when I complie a few new sections I am working on. Additionally, I plan to make an identical copy using `Python` code rather than `Matlab` to make it more accessible.
