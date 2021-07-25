# Pneumonia Classifier

**Name:** Pneumonia Classifier

**Author:** Sharome Burton

**Date:** 07/25/2021

**Description:** Machine learning model used to determine the presence of pneumonia in a patient given an image of a chest X-ray.

**Kaggle:** https://www.kaggle.com/sharomeethan/pneumonia-classifier

<img src="https://i.imgur.com/jZqpV51.png"
     alt="pneumonia-examples"
     style="left; margin-right: 10px;" />


## 1. Problem definition
> How accurately can we identify pneumonia in the lungs of a patient given their chest X-ray?

## 2. Data
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.
   
* `/test` - the test set
* `/train` - the training set
* `/val` - the validation set


Citation: http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

Data: https://data.mendeley.com/datasets/rscbjbr9sj/2

## 3. Evaluation 

> **Goal:** Detect pneumonia in a patient from their medical imagery at >90% accuracy
