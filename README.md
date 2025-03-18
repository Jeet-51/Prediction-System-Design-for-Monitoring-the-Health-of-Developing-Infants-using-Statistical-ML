# Prediction System for Monitoring Infant Health using Statistical Machine Learning

## Overview
This repository contains the implementation of an advanced prediction system designed to monitor the health of developing infants through cardiotocography data using statistical machine learning approaches. The research was published in Design Engineering, a Scopus-indexed international journal ([View Publication](http://www.thedesignengineering.com/index.php/DE/article/view/8706)).

## Project Highlights

- **Problem Addressed**: Developed an automated classification system to distinguish between normal, suspicious, and pathological cardiotocographic (CTG) readings to reduce visual analysis errors and prevent unnecessary interventional surgeries
  
- **Data Processing**: Implemented comprehensive exploratory data analysis techniques to identify patterns and distributions of features using heatmaps, histograms, and distribution plots
  
- **Class Imbalance Solutions**: Applied advanced oversampling techniques (SMOTE and ADASYN) to address class imbalance issues, creating balanced datasets that maintained the statistical integrity of the original data

- **Model Development**: Implemented and compared five machine learning classification algorithms (Random Forest, Logistic Regression, Decision Tree, Support Vector Machine, and Naive Bayes) across three different sampling approaches

- **Performance**: Achieved 94% accuracy with the Random Forest Classifier on SMOTE-balanced data, outperforming all other model configurations

- **Hyperparameter Optimization**: Utilized Grid Search CV to identify optimal model parameters and maximize performance metrics (accuracy, precision, recall, and F1-score)

- **Clinical Impact**: Created a reliable prediction system that effectively differentiates between normal and compromised fetal health, reducing the risk of unnecessary surgical interventions and contributing to lower child mortality rates

## Technologies Used
- Python (Scikit-learn, Pandas, NumPy)
- Statistical Analysis Libraries
- Machine Learning Classification Algorithms
- Data Visualization Tools (Matplotlib, Seaborn)

## Publication
This research has been published in Design Engineering (Scopus Indexed International Journal) under the title "Prediction System Design for Monitoring the Health of Developing Infants from Cardiotocography Using Statistical Machine Learning."

## Future Work
Future enhancements will focus on implementing deep learning approaches, expanding the dataset, and incorporating real-time monitoring capabilities to further improve prediction accuracy and clinical utility.
