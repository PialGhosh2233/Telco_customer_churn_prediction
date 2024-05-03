
## Predicting Telco Customer Churn with Machine Learning 

This project focuses on the analysis of the [Telco Customer Churn dataset from Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data) to uncover patterns and predictors of churn. Churn occurs when customers discontinue their services with a company. Our goal is to use machine learning to predict churn and identify key factors that could help the company improve customer retention.

### Project Structure

#### 1. Data Preprocessing
- **Cleaning:** Remove unnecessary columns to simplify the model inputs.
- **Encoding:** Convert categorical variables into numeric format using Label Encoding.
- **Handling Missing Values:** Identify and impute or remove missing values to prepare a robust dataset for modeling.
- **Feature Scaling:** Apply MinMax scaling to numeric features to normalize data, ensuring that models perform optimally and consistently.

#### 2. Exploratory Data Analysis (EDA)
- **Visualization:** Use bar charts to visualize the distribution of churned vs. retained customers, gaining insights into the balance and skewness of the dataset.

#### 3. Predictive Modeling
- **Model Selection:** Employ various machine learning models like K-nearest neighbors (KNN), Decision Tree, and Logistic Regression to predict customer churn.
- **Evaluation Metrics:** Models are evaluated using accuracy and confusion matrices to understand the performance and error characteristics.

#### 4. Ensemble Techniques
- **Bagging:** Reduce model variance and prevent overfitting by implementing bagging techniques on base models.
- **Boosting (AdaBoost):** Increase model accuracy by focusing on misclassified instances in training datasets using AdaBoost.
- **Stacking:** Combine multiple models and use a final estimator to improve prediction accuracy.

#### 5. Performance Evaluation
- **Comparison:** Assess and compare the performance of individual models and ensemble methods, highlighting the effectiveness and improvements achieved through ensembling techniques.

### Results

The project demonstrates that ensemble methods significantly enhance the prediction accuracy over single models. Detailed comparisons of model performances are documented in the Jupyter notebooks with visualizations to support findings.
