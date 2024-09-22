# Supply Chain Fraud Detection Using Machine Learning

This project focuses on detecting fraudulent orders in supply chains using advanced data analytics and machine learning techniques. Fraud in supply chains poses significant risks to businesses, leading to financial loss and damage to reputation. This project aims to enhance fraud detection capabilities by implementing machine learning models to identify suspicious transactions and orders.

## Table of Contents
. [Key Objectives](#Key-objectives)

. [Dataset](#dataset)

. [Data Preparation](#data-preparation)

. [Machine Learning Models](#machine-learning-models)

. [Model Evaluation](#model-evaluation)

. [Conclusion](#conclusion)

## Key Objectives

**Advanced Data Analytics:** Use state-of-the-art analytics to identify unusual patterns and anomalies in supply chain data.

**Machine Learning for Fraud Detection:** Implement and compare multiple machine learning models for effective fraud detection.

**Real-Time Fraud Detection:** Enable real-time detection of suspicious orders, allowing for immediate action.

**Enhanced Supply Chain Security:** Improve the security and reliability of the supply chain by detecting and preventing fraudulent activities.
## Dataset

The dataset used for this project, DataCoSupplyChainDataset.csv, contains 180,519 rows and 53 columns related to customer orders, shipping details, and more. After cleaning, the final dataset includes 36 columns of relevant data for training and testing our machine learning models.

### Data Features:

**Customer Information:** Includes customer ID, name, and location.

**Order Information:** Details about the order, shipping time, and order status.

**Target Variable:** The variable indicating suspected fraud (SUSPECTED_FRAUD).
## Data Cleaning and Preprocessing

The dataset was carefully cleaned to remove redundant and irrelevant information. Features highly correlated with others were removed to avoid redundancy. The dataset was also balanced to ensure fair model evaluation.

### Data Cleaning Steps:
**Duplicate Removal:** Identified and removed duplicate records.

**Handling Missing Values:** NaN values were handled using imputation techniques.

**Feature Selection:** Features that had a low correlation with the target variable were removed.

**Final Dataset:** After cleaning, the final dataset consists of 180,519 rows and 36 columns.
## Machine Learning Models
Implemented multiple machine learning classifiers to detect fraudulent orders and compared their performance using evaluation metrics such as accuracy, precision, recall, and F1 score. The models evaluated include:

Logistic Regression

Random Forest Classifier

K-Nearest Neighbors (KNN) Classifier

Gaussian Naive Bayes

Decision Tree Classifier

### Best Performing Model
Among all the models, the Random Forest Classifier demonstrated the best performance with:

Accuracy: 99.57%

Precision: 95.77%

Recall: 85.29%

F1 Score: 90.23%

This model proved to be the most effective in accurately identifying fraudulent orders while maintaining a good balance between precision and recall.
## Model Evaluation

### Metrics:
Accuracy: Measures the proportion of correct predictions.

Precision: Proportion of correctly identified frauds out of all fraud predictions.

Recall: Proportion of actual frauds correctly identified.

F1 Score: Harmonic mean of precision and recall, providing a balanced evaluation metric.

### Final Model Comparison:
The Random Forest Classifier was the most effective, making it the recommended model for real-time fraud detection in supply chains.
## Conclusion

This project successfully demonstrated the use of machine learning models to detect fraudulent activities in supply chains. By implementing a robust fraud detection system, businesses can avoid financial losses, improve operational efficiency, and maintain customer trust. The Random Forest Classifier emerged as the best-performing model, providing a balance of accuracy, precision, and recall.
