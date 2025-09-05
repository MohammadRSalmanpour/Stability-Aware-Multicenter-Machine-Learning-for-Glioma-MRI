# Stability-Aware-Multicenter-Machine-Learning-for-Glioma-MRI

## 📌 Overview  
This repository contains the code and supplementary materials for the paper:  
Title: **Enhancement Without Contrast: Stability-Aware Multicenter Machine Learning for Glioma MRI**


This study proposes a machine learning (ML)-based approach to predict contrast enhancement in glioma imaging from non-contrast MRI, addressing safety, cost, and accessibility issues with gadolinium-based contrast agents. A stability-aware framework is introduced to select reproducible ML models across diverse multicenter datasets, ensuring robust performance. The approach enables safer, cost-effective glioma diagnosis and monitoring while maintaining diagnostic accuracy.
- Leveraging MRI scans from 4 large public datasets  
- Benchmarking 48 feature selection/extraction methods and 25 classifiers  
- Robust rotational model selection methods were implemented to rank models using five evaluation metrics: Accuracy, F1 Score, ROC-AUC Curve, Precision, and Recall, across five-fold cross-validation and three rotational analyses.

## 📂 Repository Structure  
├── ML Codes.ipynb/                   # Python scripts for ML scripts  
├── Model Selection.ipynb             # Python scripts for robust rotational model selection and scoring 
├── Supplemental File 1.xlsx          # Supplemental File 1.xlsx  presents the complete list of average rotational performances, rankings, and scores for all 1,200 CA+DRA combinations
├── Supplemental Files 2 to 4.xlsx    # Supplemental Files 2 to 4.xlsx  present rotation results, including external tests with BraTS-Africa, UCSF-PDGM, and UPENN-GBM. Supplementary Files 2, 3, and 4 provide detailed information on these rotations. Each file contains Sheets 1-5, which outline the specific features selected by each FSA, the hyperparameters used for all ML algorithms, and the results of five-fold cross-validation, including average values and standard deviations.
├── README.md                     # This file  
 



## ⁉️ Support  
For questions, contact:  
Dr. Mohammad R. Salmanpour: msalman@bccrc.ca  
