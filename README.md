# 🚢 Titanic Classification Project - Machine Learning Pipeline

## 📊 Project Overview

This project demonstrates a **complete end-to-end machine learning pipeline**, including **data preparation, feature engineering, model selection, and performance evaluation**.  
The project applies **core data analysis techniques** combined with **predictive modeling**, focusing on deriving insights and improving model performance through iterative experimentation.

Although the dataset is based on the well-known **Titanic dataset**, the process and methods showcased here are **relevant to real-world data science and analytics projects across industries**.

---

## 🔎 Project Goals

- **Apply feature engineering techniques** to extract meaningful patterns.
- **Compare and tune multiple machine learning models** to identify the most effective solution.
- **Evaluate model performance using relevant metrics** to ensure reliability and robustness.
- **Document the analytical process to demonstrate critical thinking and data-driven decision making.**

---

## 🔨 Key Steps

### 1️⃣ Data Exploration & Cleaning
- Handling missing values through **imputation strategies**.
- Initial data profiling to understand feature distributions and potential patterns.
- Identifying key variables for **classification prediction**.

### 2️⃣ Feature Engineering
- Created **new derived features** such as:
    - Binned age categories
    - Family size feature (combining SibSp & Parch)
    - Scaled numeric columns (e.g., `Fare`) using **MinMaxScaler**.
- Exploratory feature transformations to evaluate impact on model performance.

### 3️⃣ Model Selection & Hyperparameter Tuning
- Trained and evaluated a diverse set of models:
    - 🚀 **Gradient Boosting**
    - 🌳 **Random Forest**
    - 📊 **Logistic Regression**
    - 📈 **SVM**
    - 🌐 **Naive Bayes**
    - 🌿 **Decision Trees**
- **GridSearchCV** was used to fine-tune hyperparameters for optimal performance.

### 4️⃣ Evaluation Metrics
- **Primary Metric:** F1 Score (ideal for imbalanced classification problems).
- Additional evaluation using:
    - Precision & Recall
    - Confusion Matrix
    - Cross-validation to validate robustness across different data splits.

---

## 📈 Final Results

- The **Gradient Boosting Classifier** emerged as the top-performing model after comprehensive tuning and evaluation.
- Final analysis included performance comparison on:
    - 🧰 **Training Data** (assessing fit quality)
    - 🧪 **Test Data** (assessing generalization to unseen data)

- Performance highlights:
    - Balanced approach to **precision vs recall**.
    - Effective handling of **feature importance analysis** to understand the strongest predictors.

---

## 💼 Key Takeaways

This project reflects my **end-to-end analytical thinking process**, blending:
- **Data exploration and cleaning techniques.**
- **Creative feature engineering to maximize information gain.**
- **Systematic model comparison and validation.**
- **Clear documentation for reproducibility and transparency.**

These skills are essential for any **Data Analyst** or **Machine Learning-focused Analyst** role, where understanding the data and deriving actionable insights is just as important as predictive performance.

---

## 📂 Repository Highlights

| Section | Description |
|---|---|
| 📊 Data Exploration | Jupyter Notebooks with initial profiling, visualizations, and cleaning |
| 🔎 Feature Engineering | Code for new feature creation and transformation |
| 🏆 Model Comparison | Results of cross-validation, grid search, and final model performance |
| 📑 Documentation | Process write-ups, analysis summaries, and final conclusions |

---

## 🎯 Why This Matters
This project is not just a technical exercise — it demonstrates my ability to:
- **Ask the right questions.**
- **Explore data creatively.**
- **Build and test solutions iteratively.**
- **Present findings in a clear, business-oriented manner.**

---

## 📬 Contact
For further information, feel free to visit my GitHub profile:  
[Itay Vazana on GitHub](https://github.com/ItayVazana1)

---

## ⭐ If you find this project insightful, don't forget to star the repository!
