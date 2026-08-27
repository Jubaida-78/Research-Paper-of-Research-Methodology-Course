# Research-Paper-of-Research-Methodology-Course
# An Explainable Artificial Intelligence Framework for Early Prediction of Chronic Kidney Disease Using Electronic Health Records

## Overview

This repository contains the source code, experimental results, visualizations, and LaTeX source files associated with the research paper:

**An Explainable Artificial Intelligence Framework for Early Prediction of Chronic Kidney Disease Using Electronic Health Records**

The study investigates machine learning approaches for early prediction of chronic kidney disease using electronic health record data, with emphasis on explainability, external validation, and age-group performance analysis.

## Research Objectives

- Develop machine learning models for CKD prediction.
- Evaluate model performance using multiple evaluation metrics.
- Investigate external validation performance.
- Analyze feature importance and model explainability.
- Examine performance across different age groups.

## Models

The study evaluates machine learning models including:

- Logistic Regression
- Random Forest
- Support Vector Machine
- XGBoost
- Other models included in the experimental analysis

## Repository Structure

```text
code/       Source code
figures/    Figures used in the paper
results/    Experimental results
paper/      LaTeX source and final PDF

Research-Paper/
│
├── README.md
│
├── code/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── explainability.py
│
├── figures/
│   ├── Figure_1_External_Confusion_Matrix.jpg
│   ├── Figure_2_Internal_External_ROC.jpg
│   ├── Figure_3_Feature_Importance.jpg
│   └── Figure_4_Age_Group_Fairness.jpg
│
├── results/
│   ├── model_results.csv
│   └── confusion_matrices/
│
├── paper/
│   ├── main.tex
│   ├── references.bib
│   └── Research_Paper.pdf
│
├── requirements.txt
│
└── .gitignore
