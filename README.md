💳 Credit Card Fraud Detection

📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The goal is to classify transactions as Normal or Fraudulent and identify patterns that can help detect suspicious transactions.

The project covers the complete Data Science workflow, including data understanding, data cleaning, exploratory data analysis, handling class imbalance, feature scaling, model building, and model evaluation.

---

🎯 Objectives

- Analyze credit card transaction data.
- Identify fraudulent transactions.
- Handle imbalanced transaction classes.
- Apply feature scaling.
- Build a Machine Learning classification model.
- Evaluate model performance using multiple metrics.
- Identify important features influencing fraud detection.

---

📂 Dataset

The dataset contains credit card transaction information with features such as:

- "Time"
- "V1" to "V28"
- "Amount"
- "Class"

The "Class" column is the target variable:

- "0" → Normal Transaction
- "1" → Fraudulent Transaction

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

---

🔍 Project Workflow

1. Data Understanding

The dataset was explored to understand:

- Dataset shape
- Column names
- Data types
- Missing values
- Duplicate records
- Statistical summary
- Target variable distribution

2. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Infinite values

Duplicate records were removed where required.

3. Exploratory Data Analysis

EDA was performed to understand:

- Normal vs fraudulent transactions
- Transaction amount distribution
- Transaction time distribution
- Relationship between transaction amount and fraud
- Feature correlations

4. Handling Class Imbalance

Fraudulent transactions are much fewer than normal transactions. Therefore, SMOTE (Synthetic Minority Over-sampling Technique) was applied to the training data to balance the classes.

SMOTE was applied only to the training set to avoid data leakage.

5. Feature Scaling

"StandardScaler" was used to standardize the numerical features before model training.

6. Machine Learning Model

A Logistic Regression model was trained to classify transactions into:

- Normal
- Fraudulent

7. Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

8. Feature Importance

Logistic Regression coefficients were analyzed to identify the features that had a stronger influence on fraud prediction.

---

📊 Visualizations

The project includes visualizations such as:

- Normal vs Fraudulent Transaction Distribution
- Transaction Amount Distribution
- Transaction Amount by Class
- Transaction Time Distribution
- Correlation Heatmap
- Class Distribution After SMOTE
- Confusion Matrix
- ROC Curve
- Top 10 Important Features

---

🤖 Machine Learning Model

Logistic Regression

Logistic Regression was selected because this is a binary classification problem where the target variable contains two classes:

0 = Normal
1 = Fraudulent

The model predicts the probability of a transaction belonging to the fraudulent class.

---

📈 Model Evaluation Metrics

The model performance was evaluated using:

Metric| Purpose
Accuracy| Measures overall correct predictions
Precision| Measures how many predicted fraud cases were actually fraudulent
Recall| Measures how many actual fraud cases were detected
F1-Score| Provides a balance between Precision and Recall
ROC-AUC| Measures the model's ability to distinguish between the two classes

For fraud detection, Recall is especially important because missing an actual fraudulent transaction can be costly.

---

💡 Key Learnings

Through this project, the following concepts were implemented:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Imbalanced Data Handling
- SMOTE
- Feature Scaling
- Logistic Regression
- Classification Metrics
- Confusion Matrix
- ROC-AUC Analysis
- Feature Importance

---

🏁 Conclusion

The Credit Card Fraud Detection project demonstrates how Machine Learning can be applied to a real-world financial fraud detection problem.

The complete workflow, from data preprocessing and exploratory analysis to model training and evaluation, was implemented using Python and popular Data Science libraries.

The project also highlights the importance of handling imbalanced datasets correctly and using evaluation metrics such as Precision, Recall, F1-Score, and ROC-AUC instead of relying only on accuracy.

---

👩‍💻 Author

Shabeena Bano

B.Tech CSE | Aspiring Data Scientist

---
⭐ If you find this project useful, feel free to explore the repository and connect with me.
