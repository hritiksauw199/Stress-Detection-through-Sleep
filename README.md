# Stress-Detection-in-and-through-Sleep
Considering today’s lifestyle, people are so indulged in other activities
they sacrifice sleeping hours which negatively affects their health.

In this project we analyze different parameters related to sleep
cycle that affect stress level, using 5 machine learning models:
`Logistic Regressor`, `Decision Tree`, `Random Forest`, `KNN` and `ADABoost`.
We train the models and tune their hyperparameters to gain the highest accuracy.
Lastly, we compare the highest weighted features of each models with stress level and 
draw our conclusions.

Dataset Link: https://www.kaggle.com/datasets/laavanya/human-stress-detection-in-and-through-sleep

In SayoPillow.csv, we will see the relationship between the parameters:
* snoring range of the user
* respiration rate
* body temperature,
* limb movement rate,
* blood oxygen levels, 
* eye movement, 
* number of hours of sleep, 
* heart rate
* Stress Levels (0- low/normal, 1 – medium low, 2- medium, 3-medium high, 4 -high) 

that has been generated from Literature Review.

# Steps carried out
1. Importing Libraries and Loading Dataset
2. Data Cleaning

   (Dealing with Missing values and Duplicates)
3. Standardizing Data with MinMaxScaler
4. Logistic Regression

   (Performing Logistic Regression on different features to identify model with the best accuracy.)
5. Decision Tree

   (Training with different depths to identify model with the best accuracy).
6. Random Forest

   (Tuning with different max_features and n_estimators for model with the best accuracy).
7. KNN

   (Training with different number of neighbors)
8. Adaboost

   (Tuning number of estimators to output the best model)
9. Analyzing different parameters/features that affect stress level.
****

# Libraries Used

## Data Analysis
`numpy`, `pandas`, `seaborn`, `matplotlib`, `ClassBalance`

## Machine Learning

`preprocessing`, `train_test_split`, `accuracy_score`, `precision_score`, `recall_score`,
`confusion_matrix`, `classification_report`, `SVC`, `kl`

#### Logistic Regressor
`LogisticRegression`

#### Decision Tree & Random Forest
`DecisionTreeClassifier`, `RandomForestClassifier`

#### KNN
`KNeighborsClassifier`

#### ADABoost
`AdaBoostClassifier`