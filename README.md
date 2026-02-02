# FraudLens: Interpretable Machine Learning for Proactive Financial Fraud Detection

This project presents an end-to-end machine learning solution for detecting fraudulent financial transactions, developed as part of the Accredian Data Science screening assignment. Using a large-scale transactional dataset, the solution combines statistical analysis, feature engineering, and tree-based models to identify fraud patterns with high recall while maintaining business interpretability.

The workflow includes data cleaning, outlier handling, multicollinearity reduction, and feature engineering focused on balance behavior and transaction dynamics. A Random Forest–based fraud detection model is trained and evaluated using fraud-appropriate metrics such as Precision, Recall, F1-Score, and ROC-AUC, ensuring effectiveness on highly imbalanced data.

Key insights reveal that fraudulent transactions are strongly associated with high-value TRANSFER and CASH_OUT operations, abrupt depletion of sender balances, and anomalous destination balance behavior. Beyond modeling, the project translates these insights into actionable fraud prevention strategies, including real-time monitoring, step-up authentication, and continuous model retraining.

Overall, this project demonstrates a production-ready, interpretable, and scalable fraud detection framework that bridges data science with real-world financial risk management.

🧠 Skills Demonstrated

Exploratory Data Analysis (EDA)

Feature Engineering & Multicollinearity Handling

Imbalanced Classification

Random Forest / Ensemble Models

Model Evaluation (ROC-AUC, Recall-focused metrics)

Business-driven ML Interpretation

Fraud Prevention Strategy Design
