# Bank_Customer_Churn_Prediction_and_Analysis

This project focuses on predicting **customer churn**, in banking sector which refers to the process where customers stop availing banking services. Churn prediction helps banks identify customers likely to leave, enabling them to take proactive steps to retain these customers and enhance their satisfaction.

## Project Overview

This end-to-end machine learning project involved the following steps:

### 1. Data Understanding and Cleaning

- Analyzed a dataset containing features such as **age, gender, credit score, tenure, balance, number of products,** and a target column indicating churn status.
- Ensured data quality by addressing missing values and inconsistencies.

### 2. Data Transformation

- Converted **categorical column** (e.g., gender, geography) into numerical format using encoding techniques.

### 3. Data Preprocessing 

- Addressed skewness in numerical feature to ensure better model performance.
- Treated outliers using the **Interquartile Range (IQR)** method.

### 4. Exploratory Data Analysis (EDA)

- Used **Matplotlib** and **Seaborn** to create visualizations and analyze key patterns, such as:
  - Churn distribution across demographics and account features.
  - Correlation between customer attributes and churn.

### 5. Machine Learning

- Applied various classification algorithms to predict churn includingL
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Decision Tree**
  - **Random Forest**
- Evaluated the models using metrices such as accuracy, precision, recall, and F1-Score.

 ### 6. Key Insights

 - **Random Forest** emerged as the best-preforming model, delivering the highest accuracy of **86%** and providing reliable churn predictions.

## Conclusion 

This project enhanced my skills in data analysis, preprocessing, visualization, and machine learning. The insights gained can help banks develop effective strategies to improve customer retention and satisfaction.

## Tools and Technologies

- **Programming Language:** Python.
- **Libraries:** Pandas, NumPy, Matplotlib,Seaborn, Scikit-learn.
