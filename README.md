# Predictive-Models-on-SECOM-dataset
Predictive Models for Equipment Fault Detection in the Semiconductor Manufacturing Process

## Dataset
SECOM is for modern semi-conductor manufacturing process which is normally under consistent surveillance via the monitoring of signals/variables collected from sensors and or process measurement points. However, not all of these signals are equally valuable in a specific monitoring system. The measured signals contain a combination of useful information, irrelevant information as well as noise. It is often the case that useful information is buried in the latter two. Dataset link: One can download the dataset from [SECOM](https://archive.ics.uci.edu/dataset/179/secom)

## Implementations
In this project, we have applied the followings which is crucial for carrying out to build a perfect machine learning model
- Data cleaning
- Feature engineering
- Feature Selection
    - Chi-square
    - Correlation Analysis
    - PCA
- Class balancing
    - with SMOTE
    - with SMOTE and Feature Selection Filter method
- Applying multiple predictive models
    - Decision tree
    - Logistic Regression
    - SVM
    - Random Forest
    - Gradient Boost
    - Naive Bayes
    - K-Nearest Neighbour
    - XGBOOST
- Visualization using matplotlib and seaborn 
## Code 
Here is the code implementation in google colab: <a target="_blank" href="https://colab.research.google.com/drive/1qANHGG0a9q3QX4mYbQ-HTRQdW0P-biCw?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
