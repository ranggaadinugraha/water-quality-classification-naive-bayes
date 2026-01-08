# 💧 Water Quality Classification using Naive Bayes

This project aims to classify **water quality** as **safe** or **unsafe** based on chemical and physical parameters using **Machine Learning**.  
The main algorithm used is **Gaussian Naive Bayes**, and the model is evaluated using several performance metrics and cross-validation.

---

## 📌 Project Objective
- To build a machine learning model that predicts water quality.
- To evaluate model performance using classification metrics.
- To validate model stability using Stratified K-Fold Cross Validation.

---

## 🧰 Technologies & Libraries
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Scikit-Learn  

---

## 📂 Dataset Description
The dataset contains several water quality parameters such as:
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity
- and other related features

**Target Variable**
- `is_safe = 1` → Safe water  
- `is_safe = 0` → Unsafe water  

Number of samples used: **1000 records**

---

## ⚙️ Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Check data structure and missing values  
4. Split data into features (X) and target (Y)  
5. Train-test split (70% training, 30% testing)  
6. Train Gaussian Naive Bayes model  
7. Evaluate model performance  
8. Perform Stratified K-Fold Cross Validation  
9. Visualize results  

---

## 🧠 Machine Learning Model
### 🔹 Gaussian Naive Bayes
Gaussian Naive Bayes was chosen because:
- It is fast and efficient
- Works well with multiple numerical features
- Suitable as a baseline classification model

---

## 📊 Model Evaluation
The model is evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, and F1-Score  
- Classification Report  
- Stratified K-Fold Cross Validation (10 folds)

Add your result images here:
```text
assets/
├── confusion_matrix.png
├── classification_report.png
└── cross_validation_plot.png
