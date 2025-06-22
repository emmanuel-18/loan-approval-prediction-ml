# 🏦 Loan Approval Prediction using Machine Learning

This project is a practical application of the skills I learned in [Andrew Ng's Machine Learning Specialization (Course 2)](https://www.coursera.org/specializations/machine-learning-introduction). The goal is to predict whether a loan application will be approved or not using supervised learning models.

## 📌 Objectives

- Apply concepts learned in Course 2 of the ML Specialization
- Practice end-to-end machine learning workflow
- Learn data cleaning, preprocessing, modeling, and evaluation
- Compare models (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting)
- Analyze feature importance and tune model performance

## 📊 Dataset

The dataset used in this project is a public dataset for loan prediction, containing 614 records and 13+ features like:
- Gender, Married, Education, Self Employed
- ApplicantIncome, LoanAmount, Credit History, etc.

## 🧪 Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## 🎯 Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~0.78 |
| Decision Tree       | ~0.69 |
| Random Forest       | ~0.77 |
| Gradient Boosting   | ~0.78 |

## 🧠 Key Learnings

- Handling missing values using mode/mean
- One-hot encoding for categorical features
- Scaling data using `StandardScaler`
- Avoiding data leakage during preprocessing
- Understanding feature importance from models
- Model evaluation using accuracy score
- Model persistence using `.pkl` files

## 🗂 Files

- `loan_approval_notebook.ipynb` – Complete notebook with code and explanations
- `loan_approval_model.pkl` – Saved ML model for future use (optional)
- `loan_data.csv` – Dataset used for training/testing (optional if small)
- `README.md` – Project overview

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## 📩 Contact

For feedback or questions, feel free to reach me via [LinkedIn](https://www.linkedin.com) or email.
