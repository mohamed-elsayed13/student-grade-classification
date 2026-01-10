# 🎓 Student Performance Prediction using Machine Learning

This project explores the use of multiple machine learning models to predict student performance categories based on academic and behavioral features.

## 📌 Problem Statement
The goal is to classify students into performance categories using structured tabular data, while addressing class imbalance and avoiding feature leakage.

## 🧠 Models Used
- Logistic Regression
- Random Forest
- XGBoost
- Neural Network (PyTorch)

## 📊 Evaluation Metrics
- Accuracy
- Macro F1-Score (primary metric due to class imbalance)

## ⚙️ Methodology
1. Data preprocessing and feature scaling
2. Train/test split
3. Handling class imbalance using class weights
4. Model training and evaluation
5. Feature leakage analysis by removing GPA-related features
6. Performance comparison and visualization

## 📈 Key Findings
- XGBoost achieved the best overall performance on tabular data
- Logistic Regression showed strong generalization after GPA removal
- Neural Networks underperformed due to limited data size and feature richness
- Macro F1-score provided more meaningful insights than accuracy alone

## 📂 Repository Structure
├── grade-code-prediction.ipynb
├── Student_performance_data _.csv
├── student_grade_presentation.html
├── README.md
## 🚀 Future Improvements
- Hyperparameter tuning (GridSearch / Optuna)
- Cross-validation
- Feature engineering
- Model interpretability (SHAP / feature importance)
- Dataset expansion

## 🛠 Technologies
- Python
- scikit-learn
- XGBoost
- PyTorch
- Matplotlib

## 📜 License
This project is for educational and research purposes.
