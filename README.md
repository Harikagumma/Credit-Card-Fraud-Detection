Project: Credit Card Fraud Detection (2023 Kaggle Dataset)
📄 Dataset
Source: Kaggle – 2023 Credit Card Fraud Detection

Balanced dataset: ≈500,000 rows with ~50% fraud and ~50% non-fraud cases

🚀 Model
Algorithm: XGBoost Classifier

No resampling or SMOTE used — dataset was already balanced

Trained using train_test_split (70% training, 30% testing)

📊 Evaluation Metrics
✅ Confusion Matrix:

               Predicted
              |   0   |   1
         ---------------------
Actual   0   | 93684 |    9
         1   |   39  | 93916
✅ Classification Report:
Metric	Class 0 (Non-Fraud)	Class 1 (Fraud)
Precision	1.00	1.00
Recall	1.00	1.00
F1-score	1.00	1.00
Support	93,693	93,955

✅ Accuracy:
99.97% on test data
