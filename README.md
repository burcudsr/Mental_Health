# 🧠 Mental Health Prediction

This project focuses on predicting mental health conditions using machine learning, providing insights based on comprehensive survey data. The model aims to assist in understanding patterns related to mental well-being in professional and personal environments.

### 🚀 Live Demo
Explore the interactive prediction model here: https://huggingface.co/spaces/bdaser/Mental_Health

### 📊 Dataset & Preprocessing
The dataset provides a multifaceted view of mental health indicators. To ensure the model processes these diverse inputs effectively, the following steps were taken:
* **Missing Value Imputation**: All missing values in the dataset have been systematically identified and filled with appropriate  methods to maintain data integrity and prevent information loss.
* **Data Transformation**: Categorical survey responses were encoded into numerical formats to allow for mathematical modeling.
* **Feature Scaling**: To maintain the integrity of feature importance, `StandardScaler` was applied to normalize the numerical variables, ensuring each feature has a mean of 0 and a standard deviation of 1.
* **Feature Selection**: Relevant indicators were carefully selected to capture the most significant correlations with the target variables.
* 
### 🤖 Model Performance
Various classification algorithms were tested to determine the most effective approach for predicting mental health outcomes. The results are summarized below:

| Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- |
| 0.868 | 0.871 | 0.865 | 0.868 |
