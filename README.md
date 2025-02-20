# RMS Titanic Survival Prediction using Support Vector Machine (SVM)

### Overview
This repository contains an experiment applying Support Vector Machine (SVM) to the classic RMS Titanic dataset to predict a passenger's chances of survival. The goal is to explore SVM's performance on this classification task and analyze the impact of different features on the predictions.

### Dataset
The dataset used in this experiment is the Titanic - Machine Learning from Disaster dataset, available on [Kaggle](https://www.kaggle.com/competitions/titanic). It includes information such as:
- Passenger class (Pclass)
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket fare (Fare)
- Embarked port
- Survival status (target variable: Survived)

### Implementation
The experiment follows these steps:
- Load and preprocess the dataset (handling missing values, encoding categorical features, and feature scaling).
- Split the data into training and test sets.
- Train an SVM classifier with different kernel functions.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Visualize results and feature importance.

### Requirements
To run this experiment, you need the following dependencies:
```
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Acknowledgments
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic)
- Scikit-learn for SVM implementation

<br><br>

> [!NOTE]  
> Created for the Machine Learning course, taught by Prof. Dr. Sérgio Côrtes at IESB.

