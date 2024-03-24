## Capstone Project Overview

The business challenge addressed in this capstone project revolves around the detection of potential frauds, aiming to prevent customers from being erroneously charged for items they did not purchase. With the escalating prevalence of credit card fraud in recent years, there's an urgent need to enhance risk management practices effectively. Building an accurate and user-friendly credit card risk monitoring system is imperative to address this challenge. Leveraging various machine learning algorithms, the primary objective of this project is to construct a user model adept at identifying fraud cases efficiently.

### Project Pipeline Summary:

1. **Data Understanding:** Initially, we loaded the dataset and examined its features.

2. **Exploratory Data Analytics (EDA):** This phase involved performing univariate and bivariate analyses to understand relationships, particularly focusing on the association between Amount, Time, and class. The dataset underwent scrutiny for skewness, and power transformation was employed to mitigate potential issues during model building.

3. **Train/Test Split:** The data was partitioned into training and testing sets to evaluate model performance with unseen data. Validation was conducted using the Stratified k-fold cross-validation method.

4. **Model Building/Hyperparameter Tuning:** The final step involved experimenting with various models and fine-tuning their hyperparameters to achieve the desired level of performance. Hyperparameter tuning utilized popular methods such as RandomizedSearchCV and GridSearchCV available in scikit-learn.
