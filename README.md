# Cardiovascular Risk Prediction

## 📌 Project Overview
This project predicts the **10-year risk** of Coronary Heart Disease (CHD) in patients from the Framingham Heart Study dataset.  
We use **machine learning classification algorithms** to analyze patient data, focusing on **Recall** and **F1-score** to minimize false negatives — ensuring that high-risk patients are not missed.

---

## 👥 Contributors
- M Jeevan — Roll No: 22H51A6739  
- O Shiva Kumar Reddy — Roll No: 22H51A6740  
- P Rakesh — Roll No: 22H51A6741  
- P Pavan Sai — Roll No: 22H51A6742  

---

## 📊 Dataset Information
- **Source:** Framingham Heart Study  
- **Records:** ~3390  
- **Attributes:** 16 (Demographic, behavioral, and medical factors)  

---

## 🔍 Project Workflow
1. **Import Dataset & Libraries**  
2. **Exploratory Data Analysis (EDA)** — Identifying trends and data distribution.  
3. **Data Cleaning** — Removing outliers and handling null values.  
4. **Feature Transformation** — Scaling and encoding data for ML models.  
5. **Handling Imbalanced Data** — Using **SMOTE** to balance classes.  
6. **Model Building** — Training multiple classification models.  

   **Models and Accuracy Achieved:**
   - Logistic Regression — **85.49%**
   - K-Nearest Neighbors (KNN) — **82.59%**
   - Support Vector Machine (SVM) — **84.47%**
   - Decision Tree Classifier — **76.28%**
   - Random Forest Classifier — **83.79%**

7. **Model Evaluation** — Comparing metrics (Recall, F1-score, Accuracy).  
8. **Hyperparameter Tuning** — Optimizing best model performance.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE)  
- **Environment:** Jupyter Notebook  

---

## 🎯 Problem Statement
Develop a predictive model for assessing the **10-year CHD risk** using patient demographic, behavioral, and medical risk factors.  
**Goal:** Minimize false negatives by optimizing for **Recall** and **F1-score** to ensure early detection and prevention.

---

## 📈 Model Metrics Focus
- **Recall:** To reduce false negatives (missing high-risk patients).  
- **F1-score:** To balance precision and recall.  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone <repository_link>
   cd <project_folder>
