# Heart-Disease-Classification

## Overview
This repository demonstrates a machine learning workflow to analyze a dataset for predicting heart disease.
**Dataset Link**:[Cardiovascular Disease Dataset](https://www.kaggle.com/code/fatmaabdulfattah/heart-disease-classification)
**Kaggle notebook**:[Heart Disease Classification](https://www.kaggle.com/code/fatmaabdulfattah/heart-disease-classification)
## 1. Libraries and Tools Used
- `Data Manipulation and Analysis:`
  numpy: Efficient mathematical operations.
  pandas: Data handling, cleaning, and manipulation.
  
- `Visualization:`
  matplotlib.pyplot: Basic visualizations.
  seaborn: Enhanced, aesthetically pleasing visualizations.
  
- `Modeling and Metrics:`
  sklearn modules:
    StandardScaler: Normalizing data for consistent scales.
    train_test_split: Splitting datasets for training/testing.
    SGDClassifier and KNeighborsClassifier: Machine learning models for predictions.
    metrics (e.g., precision_recall_curve, roc_curve): Model evaluation tools.

## 3. Data Visualization
Visualization segregates data based on the presence (target = 1) or absence (target = 0) of heart disease:

- `Age Distribution:`
Shows how age varies between individuals with and without heart disease.
sns.histplot is used for plotting.

- `Gender Distribution:`
Proportions of males and females with/without heart disease.
axes[0].pie plots gender percentages.

- `Resting Blood Pressure, Serum Cholesterol, Oldpeak, etc.:`
Analyzed using histograms or bar charts to identify trends across groups.
Example: Individuals with heart disease tend to have higher cholesterol levels.

- `Correlation Analysis:`
Heatmap (sns.heatmap) displays correlations between features, aiding feature selection.

## 4. Feature Engineering
- `Feature Selection:` Splits features (X) and target (y).
- `Scaling:` Standardized feature values using StandardScaler.


## 5. Modeling
- `SGD Classifier:` Achieved high accuracy (95%) and strong precision-recall metrics, with an AUC of 0.97.
- `KNN Classifier:` Performed well but was outperformed by the SGD model in accuracy and efficiency.
- `Model Comparison:` Visualizations like confusion matrices and ROC curves were used to compare performance, with the SGD model proving more robust.

## 6. Insights
The workflow efficiently preprocesses, visualizes, and models the dataset.
Accuracy and metrics indicate the models are effective in predicting heart disease.
Visualizations provide actionable insights into critical risk factors like age, cholesterol, and resting BP.



