# Fetal Health Classification using Gaussian Naïve Bayes in R

## Overview
This project implements a **Gaussian Naïve Bayes (GNB) classifier** in R to classify fetal health conditions based on cardiotocographic (CTG) exam features. The dataset consists of **2,126 records**, each labeled by expert obstetricians into one of three classes:

- **Normal**  
- **Suspect**  
- **Pathological**  

## Dataset
The dataset used in this project is the **Fetal Health Classification Dataset**, which contains various features extracted from CTG exams. These features include:

- **Baseline Fetal Heart Rate (FHR)**
- **Number of accelerations & decelerations**
- **Uterine contractions**
- **Abnormal short-term & long-term variability**
- **And other fetal heart monitoring indicators**

## Model & Approach
- The **Gaussian Naïve Bayes (GNB) classifier** is used because it assumes normal distribution for continuous features, making it a suitable choice for medical data classification.
- Data preprocessing includes handling missing values (if any), normalization, and feature selection.
- Model performance is evaluated using **accuracy, precision, recall, and F1-score**.


