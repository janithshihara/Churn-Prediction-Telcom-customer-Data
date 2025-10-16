# Telecom Customer Churn Prediction

This project predicts whether a telecom customer will **churn** (i.e., stop using the service) based on demographic and service usage data using **machine learning models**.  
After testing multiple classifiers, the **Random Forest Classifier** achieved the best performance.

---

## Project Overview

Customer churn is one of the biggest challenges for telecom companies.  
This project builds a **churn prediction model** that helps identify customers likely to leave the service, enabling the company to take proactive retention actions.

The notebook includes:
- Data exploration and preprocessing
- Feature encoding and scaling
- Model comparison (Decision Tree, Random Forest, XGBoost)
- Performance evaluation (confusion matrix, classification report)
- Saving trained model and encoders for reuse

---

## Models Evaluated
| Model | Cross-Validation Accuracy |
|--------|----------------------------|
| DecisionTreeClassifier | Lower |
| RandomForestClassifier | **Highest (Selected Model)** |
| XGBClassifier | Slightly lower |

The **Random Forest Classifier** was chosen due to its superior accuracy and balanced performance.

---

## 📈 Final Model Performance

| Metric | Value |
|---------|--------|
| **Accuracy** | **0.7786** |
| **Precision (Churn)** | 0.58 |
| **Recall (Churn)** | 0.59 |
| **F1-Score (Churn)** | 0.58 |
