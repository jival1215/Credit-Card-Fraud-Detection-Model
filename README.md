🏦 Credit Card Fraud Detection Model

This project builds and evaluates machine learning models to detect fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset.

📊 Project Overview

Fraud datasets are typically highly imbalanced, making accuracy a poor metric.
This project focuses on:

Handling class imbalance using class_weight="balanced" and optional SMOTE.

Training baselines: Logistic Regression & Random Forest.

Evaluating with the right metrics: ROC-AUC, PR-AUC, F1-Score.

Optimizing decision threshold to reduce missed fraud cases while controlling false positives.

🧠 Tech Stack

Python: Data preprocessing, model training, visualization

Libraries: scikit-learn, pandas, matplotlib, numpy

Techniques: Stratified splits, scaling, threshold tuning, confusion matrix analysis

📈 Results

Achieved strong ROC-AUC and PR-AUC with Random Forest

Improved recall significantly after threshold tuning

Produced clear visualizations (ROC, PR curves) for business interpretability

🔑 Key Learnings

Class imbalance mitigation is essential for fraud analytics

Threshold tuning often drives bigger performance gains than algorithm switching

PR curves are more informative than accuracy for rare-event detection

🚀 Next Steps

Explore Gradient Boosted Trees (XGBoost / LightGBM)

Deploy as an API for real-time fraud scoring

Integrate cost-sensitive evaluation to reflect financial impact
