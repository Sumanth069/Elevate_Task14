# Elevate_Task14

# Titanic Dataset – Machine Learning Model Comparison

## 📌 Project Overview
This project demonstrates a complete machine learning workflow used in industry to **compare multiple classification models** on the same dataset using consistent preprocessing and evaluation techniques.

The **Titanic dataset** is used to predict passenger survival, and multiple ML algorithms are trained and evaluated to identify the model that generalizes best.

---

## 🎯 Objectives
- Apply data preprocessing only once
- Use the same train–test split for all models
- Train and compare multiple machine learning algorithms
- Evaluate models using multiple performance metrics
- Identify overfitting and generalization behavior
- Select and save the best-performing model

---

## 📊 Dataset
- **Dataset Name:** Titanic Dataset
- **Source:** Seaborn library
- **Type:** Binary classification
- **Target Variable:** `survived`

The dataset contains passenger information such as age, gender, class, fare, and embarkation details.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Joblib

---

## ⚙️ Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 🧪 Methodology
1. Load Titanic dataset
2. Perform data cleaning and preprocessing
3. Encode categorical variables
4. Scale numerical features
5. Split data into training and testing sets
6. Train multiple ML models
7. Evaluate models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
8. Compare train vs test performance
9. Select best model based on generalization
10. Save the final model

---

## 📈 Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Overfitting Gap (Train Accuracy − Test Accuracy)**

These metrics help ensure that the selected model performs well on unseen data.

---

## 📊 Deliverables
- Model comparison table
- Performance comparison bar chart
- Saved best model (`.pkl` file)

---

## 🏆 Final Outcome
This project provides hands-on experience in **algorithm selection, model evaluation, and generalization analysis**, similar to workflows followed by industry ML teams.

It helps interns and students understand why **accuracy alone is insufficient** and how to choose models based on business and data requirements.

---

## 🚀 How to Run the Project
```bash
pip install pandas numpy scikit-learn seaborn matplotlib joblib
