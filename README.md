# E-Commerce Fraud Detection Using Machine Learning

## 📌 Project Overview

E-commerce websites handle thousands of transactions every day. Some of these transactions may be fraudulent.

This project uses Machine Learning to identify suspicious and potentially fraudulent e-commerce transactions.

The main goal is to reduce financial loss and improve the security of online transactions.

## 🎯 Objectives

- Detect potentially fraudulent transactions.
- Analyze customer purchasing behavior.
- Create useful features from transaction data.
- Compare different Machine Learning models.
- Select a suitable final model for fraud detection.
- Optimize the prediction threshold based on business cost.

## 📊 Dataset

The project uses the Online Retail II dataset.

The dataset contains information about online retail transactions such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook
- Machine Learning

## 🔄 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Handling Class Imbalance
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Threshold Optimization
11. Final Model Selection

## ⚙️ Feature Engineering

Several features were created to understand transaction and customer behavior.

### Transaction Features

- Total Amount
- Quantity
- Price
- Log-transformed features

### Customer Features

- Recency
- Frequency
- Monetary Value
- Customer Lifetime
- Average Purchase Value
- Purchase Regularity

### Behavioral Features

- Amount compared with Customer Average
- Quantity compared with Customer Average
- Amount Difference from Customer Average
- Transaction Velocity

### Risk Features

- Country Popularity
- Country Risk

## 🤖 Machine Learning Models

The following Machine Learning algorithms were evaluated:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Naive Bayes
- AdaBoost

## ⚖️ Handling Class Imbalance

Fraud detection datasets usually contain fewer fraudulent transactions compared with normal transactions.

SMOTE (Synthetic Minority Over-sampling Technique) was used to handle class imbalance during model training.

## 📈 Model Evaluation

The models were evaluated using suitable classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## 💰 Business Cost and Threshold Optimization

Instead of using only the default probability threshold, different thresholds were tested.

The total business cost was calculated for each threshold.

The threshold with the lowest business cost was selected as the optimal threshold.

## 🚀 Final Result

The final model was selected based on model performance and business cost.

The optimized threshold helps the system make fraud predictions according to the business requirements.

## 📁 Project Files

The repository contains the project notebook and supporting files used for the Machine Learning workflow.

## 🔮 Future Improvements

- Deploy the model as a web application.
- Add real-time fraud detection.
- Monitor changes in fraudulent behavior.
- Improve the model using advanced Machine Learning techniques.

## 👩‍💻 Author

**Fathimath Sahla**

Data Science & Machine Learning Enthusiast
