# 🧠 Breast Cancer Detection using Machine Learning (Voting Classifier Approach)

This repository contains a research-based machine learning project focused on early and accurate detection of breast cancer using multiple supervised learning classifiers and ensemble techniques. The goal is to enhance diagnostic reliability compared to traditional screening methods by using AI-driven techniques.

## 📌 Project Overview

Breast cancer is one of the most prevalent cancers among women, and early detection significantly improves survival rates. However, traditional methods like mammography, ultrasound, and MRI can have limitations in accuracy and accessibility. This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** and applies **eight machine learning classifiers** to compare performance and improve diagnosis accuracy through a majority-based voting system.

## 🧪 Models Used

- Artificial Neural Network (ANN)  
- Support Vector Machine (SVM)  
- Random Forest Classifier (RFC)  
- Extra Trees Classifier (ETC)  
- Nu-Support Vector Classifier (NuSVC)  
- Passive-Aggressive Classifier (PAC)  
- Extreme Gradient Boosting (XGBoost)  
- Adaptive Boosting (AdaBoost)

These classifiers were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Matthews Correlation Coefficient (MCC)

## ⚙️ Methodology

1. **Data Acquisition**  
   Utilized the Breast Cancer Wisconsin Diagnostic dataset from the UCI Machine Learning Repository.

2. **Data Preprocessing**  
   - Outlier detection using boxplots (see `boxplot and outliers.ipynb`)  
   - Missing value handling  
   - Feature selection based on correlation and significance

3. **Model Training & Evaluation**  
   - 75:25 train-test split  
   - Individual classifier training and metric analysis  
   - Confusion matrices and MCC comparison  
   - Voting ensemble classifier for final prediction

## 📊 Outlier Analysis

A separate notebook (`boxplot and outliers.ipynb`) is provided for:
- Visualizing distributions using boxplots  
- Identifying and handling outliers  
- Supporting robust model training

## 📈 Results

The voting ensemble method delivered improved accuracy and reduced both false positives and false negatives. Metrics and confusion matrices confirm the effectiveness of combining multiple models.

## 📂 Files Included

- `Breast_Cancer.csv` – Dataset used for training and testing  
- `breast_cancer_prediction_main__voting_classifiers.ipynb` – Main ML notebook  
- `boxplot and outliers.ipynb` – Preprocessing and outlier visualization  
- `Breast cancer paper.pdf` – Research paper summarizing the project

## 🏆 Highlights

- Strong performance from ensemble learning  
- Comprehensive model comparison  
- Preprocessing powered by outlier analysis and feature selection

## 📚 Citation

If you use this work, please cite:  
**"Breast Cancer Classification Using Machine Learning Ensemble Methods" – Mehuli Lahiri, 2024**

## 💡 Future Work

- Integrate deep learning models  
- Explore image-based diagnosis  
- Deploy interactive web-based diagnostic tools

