# Titanic Survival Prediction with Machine Learning

A comprehensive machine learning project that predicts passenger survival on the Titanic using various classification algorithms and data analysis techniques.


## 🚢 Overview

This project analyzes the famous Titanic dataset to predict passenger survival using machine learning techniques. The analysis includes comprehensive data exploration, feature engineering, and implementation of multiple classification algorithms to achieve optimal prediction accuracy.

## 📊 Dataset

The dataset contains information about Titanic passengers including:
- **PassengerId**: Unique identifier for each passenger
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Survived**: Survival status (0 = No, 1 = Yes)

## ✨ Features

- **Data Preprocessing**: Comprehensive data cleaning and handling of missing values
- **Exploratory Data Analysis**: Detailed visualization and statistical analysis
- **Feature Engineering**: Creation of new meaningful features from existing data
- **Multiple ML Models**: Implementation of various classification algorithms
- **Model Comparison**: Performance evaluation and comparison of different models
- **Hyperparameter Tuning**: Optimization of model parameters for better performance
- **Visualization**: Interactive plots and charts for data insights
```

## 📈 Model Performance

The final model successfully generated predictions for 418 test passengers (PassengerId 892-1309) with the following characteristics:

- **Total Predictions**: 418 passengers
- **Predicted Survivors**: 152 passengers (36.4%)
- **Predicted Non-survivors**: 266 passengers (63.6%)
- **Submission Format**: Kaggle-compatible CSV file

### Survival Prediction Distribution
- The model predicts a survival rate of approximately 36.4%, which aligns well with the historical Titanic survival rate of ~38%
- Predictions range across all passenger classes and demographics in the test set

## 🔍 Key Insights

- **Gender**: Women had significantly higher survival rates (74%) compared to men (19%)
- **Passenger Class**: First-class passengers had the highest survival rate (63%), followed by second-class (47%) and third-class (24%)
- **Age**: Children under 16 had higher survival rates, while elderly passengers (60+) had lower rates
- **Family Size**: Passengers with 1-3 family members had better survival chances than those traveling alone or in large groups
- **Embarkation Port**: Passengers from Cherbourg had slightly higher survival rates


```
```

## 🛠️ Technologies Used

- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning library
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment
- **XGBoost**: Gradient boosting framework
- **Plotly**: Interactive visualizations


## 🙏 Acknowledgments

- Kaggle for providing the Titanic dataset
- The machine learning community for inspiration and best practices
- Contributors and reviewers who helped improve this project