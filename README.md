# 🌟 Introduction to Supervised Learning  
### *Machine Learning Sessional*
This document provides a simple, clean introduction to key machine learning concepts suitable for the first day of a lab session. It covers **Supervised Learning**, **Regression**, **Model Selection**, **Generalization**, and the **Dimensions of a Supervised Learning Algorithm**.
## 📘 1. What is Supervised Learning?
Supervised Learning is a type of machine learning where:
- The model receives **input data (X)**
- Along with the **correct output (Y)**
- It learns to map **X → Y** using examples  
It is “supervised” because the correct answers guide the learning process.
**Examples**
- Predicting house price → *Regression*
- Classifying email as spam/not spam → *Classification*
- Predicting loan approval → *Classification*
## 🏡 2. Regression (Predicting Continuous Values)
Regression is used when the target/output is a **number**.
### 🎯 Goal
Learn a function:  
`f(x) → y`  
so that the model can predict numerical values for new data.
### 🔍 Examples
- Predicting salary from experience
- Predicting temperature
- Predicting marks based on study hours
### 📈 Simple Linear Regression
`y = w*x + b`  
The model learns **w** and **b** that minimize error.
### 📏 Common Error Metrics
- **MSE** (Mean Squared Error)
- **RMSE**
- **MAE**
## 🔎 3. Model Selection
Model Selection is the process of choosing the **best model** for your dataset.
We evaluate models using:
### ✔ Training Data  
Used to learn the model.
### ✔ Validation Data  
Used to tune and compare models.
### ✔ Test Data  
Used only at the end for final performance evaluation.
### 🔑 Model Selection Tools
- Train/Validation/Test Split
- k-Fold Cross Validation
- Grid Search / Random Search
- Regularization techniques (L1, L2)
**Why?**  
To avoid selecting a model that looks good on training data but fails on new data.
## 🎯 4. Generalization
Generalization is the model’s ability to perform well on **new, unseen data**.
### ⚠ Overfitting
- Very low training error
- High test error
- Model memorizes the data
### ⚠ Underfitting
- High training and test error
- Model too simple
### ✅ Good Generalization
- Low training error
- Low test error
- Model captures true patterns, not noise
## 📐 5. Dimensions of a Supervised Learning Algorithm
A supervised ML algorithm is defined by several key dimensions:
### 1️⃣ **Hypothesis Space**
Set of all models the algorithm can choose from (e.g., linear models, decision trees, neural networks).
### 2️⃣ **Model Complexity**
Too complex → Overfitting  
Too simple → Underfitting
### 3️⃣ **Loss Function**
Measures how wrong the model is (e.g., MSE, cross-entropy).
### 4️⃣ **Optimization Method**
How the model updates parameters (e.g., Gradient Descent, SGD).
### 5️⃣ **Regularization**
Techniques to prevent overfitting (e.g., L1, L2).
### 6️⃣ **Data Requirements**
Amount of data, number of features, noise level.
## 🧾 Summary Table
| Concept | Meaning | Example |
|--------|---------|---------|
| **Supervised Learning** | Learning from labeled data | House price prediction |
| **Regression** | Predicting continuous values | Salary, temperature |
| **Model Selection** | Choosing best model | Cross-validation |
| **Generalization** | Performance on unseen data | Test accuracy |
| **Model Dimensions** | Characteristics of learning | Loss, complexity, GD |



need to search for paper

