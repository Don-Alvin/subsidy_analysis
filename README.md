# Subsidy Fraud Detection Analysis

## Overview  
This project analyzes subsidy disbursement data to detect potential fraudulent activities using both unsupervised and supervised machine learning techniques. The analysis includes exploratory data analysis, anomaly detection with Isolation Forest, and fraud classification with Random Forest.

## Features  
- Comprehensive EDA with demographic and subsidy pattern visualizations  
- Data cleaning and preprocessing pipeline  
- Anomaly detection using Isolation Forest  
- Fraud classification with Random Forest (optimized via GridSearchCV)  
- Handling of class imbalance using SMOTE  
- Performance metrics including ROC-AUC, precision-recall, and confusion matrices  

## Requirements  
- **Python 3.7+**  
- **Required packages**:  
  ```bash
  pandas
  numpy
  seaborn
  matplotlib
  scikit-learn
  imbalanced-learn