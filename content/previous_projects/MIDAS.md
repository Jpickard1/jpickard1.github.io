---
title: Michigan Institute of Data Science
---

<img src="https://github.com/Jpickard1/jpickard1.github.io/blob/main/content/imgs/MIDAS%20logo.png?raw=true" alt="MIDAS logo" object-fit="fill" align="left" width="200px"/>

During the summer of 2021, I was an instructor for the [Data Science for Biomedical Scientist](https://midas.umich.edu/data-science-for-biomedical-scientists/) workshop. This one week course covered the fundamentals of data science and introductory machine learning. I developed and taught programming lectures that applied different algorithms to biological and clinical data. The programming lectures followed conceptual lectures on how each algorithm worked and different clinical use cases for them.

The code and the data are now available in google colab notebooks below, and the original git repo can be found here: https://github.com/Jpickard1/MIDASBioMedBootCamp. Each notebook contains a description of the data used and some instructions for how to run the code. Ning Ping was an instructor for this course and coauthored these notebooks with me.

### [Introduction to Python](https://drive.google.com/file/d/1q35hXryQsIgfSSjxQGRR1RiIIQ053DCj/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1q35hXryQsIgfSSjxQGRR1RiIIQ053DCj/view?usp=sharing) covers the basic syntax and programming operations in python. It is a brief overview of variables, control flow, and data structures. It is very acceessable to anyone that has written code in another language before.

### [Clustering](https://drive.google.com/file/d/1O8ul-jx1XnM_MbPIchyS70SbtZz9b54A/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1O8ul-jx1XnM_MbPIchyS70SbtZz9b54A/view?usp=sharing) introduces K-Means, Spectral, and Aglomerative clustering techniques on multiple simulated datasets. It provides documentation for a number of other clustering algorithms as well and introduces how to evaluate the quality of a clustering using Davis-Boulding Scoring.

### [Regression and Naive Bayes](https://drive.google.com/file/d/1pW0dWgiDtyRJ2tjcXWl8F7MqUlm4kQW9/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1pW0dWgiDtyRJ2tjcXWl8F7MqUlm4kQW9/view?usp=sharing) applies linear, logistic, and ridge regression techniques to a datasets with information on systolic blood pressure and a dataset about the effects of smoking during pregnancy. It also introduces different methods exploring a data set and evaluating a models performance. The Naive Bayes model is applied to predict a diagnosis of diabetes in patients.

### [Decision Trees](https://drive.google.com/file/d/1O4I8vNNR6inoTpIkDw521ELJQ8mtCfat/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1O4I8vNNR6inoTpIkDw521ELJQ8mtCfat/view?usp=sharing) explores the Wisconsin Breast Cancer Dataset using decision trees.

### [Random Forests](https://drive.google.com/file/d/1ucz5SvcncT3A9qWIBjOx8EPl4o1G0Zfy/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1ucz5SvcncT3A9qWIBjOx8EPl4o1G0Zfy/view?usp=sharing) looks at heart disease prediction using a dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart%2BDisease) and a [Kaggle competition](https://www.kaggle.com/shahirzain/heart-disease-prediction).

### [Support Vector Machines](https://drive.google.com/file/d/1w_kQ0zBKiPyMsFZNLDhkiz1acR7YLM84/view?usp=sharing)

This was my favorit [notebook](https://drive.google.com/file/d/1w_kQ0zBKiPyMsFZNLDhkiz1acR7YLM84/view?usp=sharing). It explores Support Vector Machines with mutliple kernel configurations on simulated data, the Iris dataset, and the Wisconsin Breast Cancer Dataset.

### [Neural Networks](https://drive.google.com/file/d/1C9DwJtgmznNoGTZB8uupWbKjgD_5TQIq/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1C9DwJtgmznNoGTZB8uupWbKjgD_5TQIq/view?usp=sharing) builds a basic neural network using keras. Note this colab notebook currently relies on additional import files to deal with the data set, so it can't be run from colab. However, the expected output can be seen and the notebook and required files can be found in the git repo. To run this notebook locally, it can be cloned from the [git repo](https://github.com/Jpickard1/MIDASBioMedBootCamp) and found in Session 15.

### [Long Short Term Memory Neural Networks](https://drive.google.com/file/d/1PAYOQCvOJzn4X4MgiuWOPW7dk4fbXBu1/view?usp=sharing)

This [notebook](https://drive.google.com/file/d/1PAYOQCvOJzn4X4MgiuWOPW7dk4fbXBu1/view?usp=sharing) builds a Long Short Term Memory Neural Network to do time series data analysis using the Human Activity Recognition Using Smartphones Data Set. This dataset has movement data collected from a cell phone that a number of participants held while doing different activities. The goal is to build a neural network that can identify the what the person is doing. Similar to the neural network above, this notebook should be run locally and cloned from the [git repo](https://github.com/Jpickard1/MIDASBioMedBootCamp) (found in Session 20). The expected output can be seen in the colab notebook.
