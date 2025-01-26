# Breathing Sound Classification Project

This project focuses on classifying breathing sounds into two categories: **Normal** and **Wheezing** (commonly associated with asthmatic patients). 
The following steps outline the process:

## Dataset Overview
  - `Normal`: Recorded sound waves of normal breathing.
  - `Wheezing`: Recorded sound waves of breathing with a wheezing sound.

## Steps to Complete
1. **Labeling and Data Split**:
   - Assign labels to the dataset:
     - Files from `Normal`: **Label as 0**.
     - Files from `Wheezing`: **Label as 1**.
   - Split the data into:
     - **Training set**: 80% of files from each class.
     - **Testing set**: 20% of files from each class.

2. **Feature Extraction**:
   - Experiment with different feature extraction techniques, such as:
     - Persistent Entropy.
     - Carlsson Coordinates.
     - Other suitable methods.
   - Test and compare various feature extraction techniques to identify the best-performing ones.

3. **Model Training and Evaluation**:
   - Train classification models using the processed dataset.
   - Evaluate the models and aim for the **highest accuracy** in classifying breathing sounds.

## Goal
The main objective is to build a machine learning pipeline capable of accurately distinguishing between normal and wheezing breathing sounds. This has potential applications in medical diagnostics, particularly for conditions like asthma.

