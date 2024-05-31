# Credit - Card Default as Predicting Customer Outcomes
Credit card def
ault prediction in Taiwan involves analyzing a dataset containing various customer attributes like gender, education, age, repayment status, and bill statements to forecast potential defaults. This project aims to leverage machine learning to anticipate credit card defaults, allowing for proactive measures to minimize financial risks**.


**Problem Statement:**

We're tasked with predicting credit card defaults using a dataset featuring attributes such as gender, credit limit, education, marital status, and repayment history. The objective is to identify potential defaulters and tailor credit offerings accordingly to mitigate risks.

**Introduction:**

With a dataset comprising 30,000 rows and 25 columns, we aim to predict credit card defaults in Taiwan. Our goal is to understand the dataset, detect outliers, explore correlations, visualize data, implement models, and draw conclusions to optimize predictive accuracy.

**Steps Involved:**

* Data Summary: Analyzing the dataset to gain insights and simplify data for better comprehension.
  
* Data Preprocessing: Handling missing values, renaming columns, and preparing the data for analysis.
  
* Identifying Relationships: Utilizing correlation matrices to assess statistical relationships between variables.

* Encoding Categorical Columns: Using One Hot Encoding to convert categorical features into numerical format.
  
* Exploratory Data Analysis (EDA): Analyzing relationships between the target variable and independent variables to understand behavior.

* Feature Selection: Selecting relevant predictor features for modeling purposes.

**Models Implemented:**

Logistic Regression: Utilizing logistic regression for binary classification based on sigmoid function.

Random Forest Classifier: Employing an ensemble method to build multiple decision trees and improve classification accuracy.

**Model Performance:**

Confusion Matrix: Evaluating classification success based on predicted and actual labels.

Precision/Recall: Assessing model precision and recall metrics.

Accuracy: Measuring the ratio of correctly classified examples to the total.

Area Under ROC Curve (AUC): Evaluating overall classification performance.


**Conclusion:**

In conclusion, our analysis of credit card default prediction in Taiwan revealed that the Random Forest Classifier outperformed Logistic Regression in terms of recall and precision metrics. While Logistic Regression achieved a recall and F1-score of 78% and 73% respectively, Random Forest Classifier achieved values of 85% and 83% respectively. The higher precision of Random Forest Classifier makes it the preferred model when considering the balance between recall and precision. Therefore, for credit card default prediction in Taiwan, we recommend employing the Random Forest Classifier for its superior performance in identifying potential defaulters while minimizing false positives.







