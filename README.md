# 🏦 Bank Term Deposit Classifier

## 📌 Overview
- Predicts whether a client will subscribe to a bank term deposit using machine learning models on the Bank Marketing Dataset. 
- It helps banks identify potential clients for targeted campaigns.
- Binary classification problem: “Yes” ➡ subscribes, “No” ➡ does not subscribe

## ⚙ Process
- **Data Cleaning:** Handled missing values, drop duplicate rows, encode categorical data
- **Feature Analysis & EDA:** Explored relationships between client features and subscription
- **Models:** Linear Classifier & Logistic Regression
- **Evaluation:** Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 📊 Results Summary
### scikit-learn Outputs
- Accuracy: 90.57% (both models)
- Precision: 0.66 ➡ very few predicted “Yes” are correct
- Recall: 0.40 ➡ few actual positives correctly predicted
- F1-Score: 0.50 ➡ balance between precision & recall

### Manual Evaluation
🔹 Linear Classifier:
- Accuracy: 88.21%
- Fails to capture positive cases ➡ precision & recall undefined

🔹 Logistic Regression:
- Accuracy: 75.91%
- Precision: 30% (correct predictions out of all predicted “Yes”)
- Recall: 75% (captures most actual positives)
- F1-Score: 0.42 ➡ trade-off between precision & recall

## 🌐 Dataset Source
The dataset titled **Bank Marketing Dataset** is taken from the https://archive.ics.uci.edu/dataset/222/bank+marketing

## 🛠 Technologies
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
