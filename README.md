# Customer Churn Prediction Model

This repository contains code for a customer churn prediction model built using Python and scikit-learn. The model predicts whether a customer will churn (leave) a subscription-based service or business based on historical customer data. The dataset used in this project is the Churn_Modelling dataset obtained from [Kaggle](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction).

## Libraries Used:

- **pandas**: Used for data manipulation and analysis.
- **scikit-learn**: Utilized for building and evaluating machine learning models.
- **warnings**: Employed to ignore warning messages during code execution.

## Usage:

1. **Data Loading and Preprocessing**: The dataset is loaded using pandas, and features relevant to the prediction task are selected while excluding non-relevant features such as 'Surname', 'RowNumber', 'NumOfProducts', 'Geography', 'Gender', and 'Tenure'. The target variable is 'Exited', indicating whether a customer churned or not.

2. **Data Splitting**: The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn. 

3. **Feature Scaling**: Standard scaling is applied to the numerical features using `StandardScaler` to ensure all features have the same scale.

4. **Encoding Categorical Variables**: Categorical variables such as 'Geography' and 'Gender' are encoded using `OneHotEncoder` and `LabelEncoder`, respectively.

5. **Model Training and Evaluation**: Three different classification models, namely Logistic Regression, Random Forest, and Gradient Boosting, are trained on the training data. The trained models are then evaluated using accuracy score and classification report metrics on the testing data.

## Model Performance:

- **Logistic Regression**: Achieved an accuracy of X% on the testing set.
- **Random Forest**: Achieved an accuracy of Y% on the testing set.
- **Gradient Boosting**: Achieved an accuracy of Z% on the testing set.

---
