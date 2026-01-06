# Confusion Matrix – Air Quality Alert Prediction

## 📌 Overview
This project demonstrates the use of a **Confusion Matrix** to **evaluate a classification model** that predicts whether air quality conditions are **Safe or Unsafe**.

Such systems are useful for **environmental monitoring**, **public health alerts**, and **smart city applications**.

---

## 🧠 Problem Statement
Given air quality conditions, the model predicts:
- **Safe** → Air quality is within acceptable limits  
- **Unsafe** → Air quality may pose health risks  

A confusion matrix helps evaluate how accurately the model identifies unsafe conditions.

---

## 🛠️ Libraries Used
- **Python**
- **NumPy**
- **scikit-learn**
- **Seaborn**
- **Matplotlib**

---

## 📂 Dataset Description
This dataset simulates real-world **air quality alert predictions**.

- **Actual labels** → True air quality status  
- **Predicted labels** → Model’s predicted status  

### Classes
- **Safe**
- **Unsafe**

The data is created using NumPy arrays for learning and demonstration purposes.

---

## ⚙️ Code Workflow
1. Import required libraries  
2. Define actual and predicted air quality labels  
3. Generate confusion matrix using `confusion_matrix()`  
4. Visualize using a heatmap  
5. Interpret the results  

---

## 📈 Output Interpretation
- **Rows** → Actual air quality condition  
- **Columns** → Predicted condition  
- **Diagonal values** → Correct predictions  
- **Off-diagonal values** → Incorrect predictions  

False negatives are critical, as unsafe air predicted as safe can be harmful.

---

## ✅ Key Features
- Environment-focused real-world problem  
- Clear visualization using heatmap  
- Easy-to-understand implementation  
- Practical ML evaluation technique  

---

## 🎯 Learning Outcome
- Understand confusion matrix interpretation  
- Learn evaluation of safety-critical classification problems  
- Gain experience with real-world ML scenarios  


