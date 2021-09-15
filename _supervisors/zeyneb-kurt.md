---
layout: supervisor
title: Zeyneb Kurt
available: true
email: zeyneb.kurt@northumbria.ac.uk
website: https://www.northumbria.ac.uk/about-us/our-staff/k/zeyneb-kurt/
office_hours: |
  Currently (this can be updated later):
  CIS 308
  Monday   15:15-16:15
  Thursday 13:15-14:15
research_group: Digital Health and Wellbeing
research_themes:
  - Artificial Intelligence
  - Deep Learning
  - Machine Learning
  - Data Science
additional_keywords:
  - Bioinformatics
  - Computational Biology
  - Health Informatics
  - Data Analytics
technologies_languages:
  - Python
  - R
additional_details: >-
  My research interests include bioinformatics, computational biology,
  statistics, image processing, and machine learning. Please see my project
  proposals below and feel free to contact me if you have any questions or if
  you want to discuss any project ideas related to my research interests. 


  Note: Experience with (or willing to learn) Python and/or R is necessary 


  **Prediction of the groups in a colon cancer cohort by integrating different types of big biological datasets**


  Aim: Predicting sub types in a colon cancer cohort by integrating DNA methylation, miRNA, and mRNA expression data collected from the same set of patients. 


  The datasets are publicly available and will be downloaded from TCGA portal (TCGA- Assembler R package can be used).


  Steps:


  1. Preprocessing data (cleaning noise, normalisation each data type individually, then combining them all, and applying a unit scale \[e.g. L2] transform) 

  2. Training an autoencoder model and identification of the best feature size (dimension can be reduced gradually, e.g. {500, 400, 300, 200, 100} ).

  3. Use the best feature size, predict the optimum 'k' value for k-means clustering among 2<=k<=10 (e.g. elbow method or silhouette index can be used)

  4. Label/group the samples based on the k-means clustering with the optimal 'k' value and compare the overall survival of the sub-populations using the ‘Kaplan-Meier’ estimator.


  **Tumor stage prediction in colon cancer with transfer learning using pathological tissue images**


  Aim: Classification of the tumor stages in a colon cancer cohort using Hematoxylin and eosin (H&E)-stained pathological tissue images. 


  Image dataset and patients' metadata are publicly available and will be downloaded from TCGA portal. Tumor stage info (and the other relevant clinical and demographics data) of each patient is available in the metadata.


  This is an image processing project and multiple CNN models (e.g. VGGXX, InceptionvXX, ResNetXX) are expected to be re-trained and compared for the tumor stage classification task.
---
