# fraud-detection-ml
Fraud Detection System using Machine Learning (Logistic Regression &amp; Random Forest)
# Fraud Detection System

## Overview
This project detects fraudulent transactions using machine learning.

## Challenge
The dataset is highly imbalanced (~0.17% fraud cases), so accuracy is not reliable.

## Models Used
- Logistic Regression
- Random Forest

## Results
- Logistic Regression:
  - High Recall (~91%) → detects most fraud cases
  - Low Precision → more false alarms
- Random Forest:
  - High Precision (~90%)
  - Low Recall → misses many frauds

## Conclusion
Logistic Regression performed better because recall is more important in fraud detection.

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Future Improvements
- Improve precision using threshold tuning
- Try advanced models like XGBoost
