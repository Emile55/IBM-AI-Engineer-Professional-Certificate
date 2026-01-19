# Credit Card Fraud Detection: Decision Tree vs. SVM Comparison

This project is part of the **IBM AI Engineer Professional Certificate**. The primary goal is to identify fraudulent credit card transactions using machine learning models trained on a highly imbalanced dataset.

## 🎯 Objectives
- Preprocess real-world financial data using **StandardScaler** and **L1 Normalization**.
- Handle class imbalance using **sample weighting** techniques.
- Benchmark and compare the performance of two classification algorithms: **Decision Tree** and **Linear Support Vector Machine (SVM)**.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, Scikit-learn, Matplotlib
- **Evaluation Metric:** ROC-AUC Score

## 📊 Results & Performance
After training and evaluating both models on the test set, the results are as follows:

| Model | ROC-AUC Score |
| :--- | :--- |
| **Decision Tree** | 0.939 |
| **Linear SVM** | **0.986** |

**Conclusion:** The SVM model demonstrated superior capability in distinguishing between fraudulent and legitimate transactions, making it the optimal choice for this high-stakes security use case.

## 📈 Key Inferences
- **Feature Scaling:** Standardizing features was essential for the SVM to converge effectively.
- **Model Selection:** While Decision Trees are more interpretable, SVMs excel in high-dimensional spaces, providing a significant boost in detection accuracy (ROC-AUC).
- **Practical Application:** The SVM model is recommended for deployment due to its high precision in identifying fraud patterns.
