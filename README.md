# Computational-Intelligence-SecondProject

Welcome to the README for our Computational Intelligence project, where we explore feature selection and segmentation to improve the accuracy and speed of a seizure detection model. This project consists of three main components: feature evaluation and selection, improved accuracy with segmentation, and evaluation with different topics.

## Project Overview

In this project, we aim to enhance the performance of our seizure detection model by carefully selecting features and implementing segmentation. Here's an overview of each component:

### Feature Evaluation and Selection

In this phase, our focus is on feature evaluation and selection. We want to identify the most valuable features for our task. We follow these steps:

1. **Feature Evaluation**: We evaluate the effectiveness of individual features using a decision tree classifier. This helps us measure the quality of each feature in isolation.

2. **Correlation Analysis**: We assess the correlation between features using index correlation. Our goal is to select features that are minimally correlated with each other.

3. **Feature Selection**: We combine the results from feature evaluation and correlation analysis to determine the most suitable features for our task. The selected features are crucial for improving the model's performance.

### Improved Accuracy with Segmentation

In the second phase, we work on enhancing the model's accuracy and speed through segmentation. This involves the following steps:

1. **Data Segmentation**: We divide the dataset into different segments using a specific algorithm. Each segment contains a subset of the data.

2. **Model Training and Testing**: We train the existing seizure detection model on each separate segment. During testing, the input is assigned to the appropriate segment, and the corresponding subsystem is used for classification.

3. **Unique System for Seizure Diagnosis**: By implementing segmentation, we create a unique system that combines the results from multiple subsystems, leading to improved accuracy and speed.

### Evaluation with Different Topics

In the final phase, we evaluate the model's performance using different classification modes, including 2-class and 3-class modes. This allows us to assess the versatility and robustness of our method.

## Dataset Description

The dataset used in this project can be accessed at the following link: [Dataset Link](https://www.upf.edu/web/ntsa/downloads/-/asset_publisher/xvT6E4pczrBw/content/2001-indications-of-nonlinear-deterministic-and-finite-dimensional-structures-in-time-series-of-brain-electrical-activity-dependence-on-recording-regi?inheritRedirect=false&redirect=https%3A%2F%2Fwww.upf.edu%2Fweb%2Fntsa%2Fdownloads%3Fp_p_id%3D101_INSTANCE_xvT6E4pczrBw%26p_p_lifecycle%3D0%26p_p_state%3Dnormal%26p_p_mode%3Dview%26p_p_col_id%3Dcolumn-1%26p_p_col_count%3D1).

## Authors

- Mehrnaz Sadeghieh
- Faridreza Momtaz Zandi

***

Thank you for exploring our Computational Intelligence project, where we focus on feature selection, segmentation, and versatile evaluation for seizure detection. We hope our work contributes to the advancement of intelligent systems in healthcare applications.
