# Titanic
Titanic ML Disaster

# Feature Enginnering

-  We have filled NA values in 'Age' column in train data using median.
- 'Fare' missing value in test is filled using median.
-  Cabin missing values are filled with 'X' character.
-  We create 'age_group' column and divide age into 4 groups `Age <= 20` , ` 20 < Age <= 40`, `40 < Age <= 60` and `Age > 60`
-  We create 'fare_group' column based upon mean of Fare for each 'Pclass'.
-  We create one hot encoding for Embarked column.
-  Combined the 'Sibsp' and 'Parch' column into 'Family' and 'Alone' and then divided into family groups based upon survival rate.
-  Mapped 'Male' and 'Female' in 'Sex' column to 0 and 1.


# Exploratory Analysis

![Image1](1.png)
![Image2](2.png)

# Results

| Classifier | Val accuracy | Submission results |
|------------| ------------ | -------------------|
| Linear SVM |              |                    |
|Non-Linear SVM (RBF Kernel) | | |
| Non-Linear SVM (Linear Kernel) | | |
| Decision Tree | | |
| XGBoost | | |
| Random Forest | | |
| Neural Netwrok | | |

# Referennces

1. https://www.kaggle.com/l3r4nd/titanic-prediction-with-svm
