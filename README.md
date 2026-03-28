# 🚀 Linear Models vs MLP (From Scratch)

> A hands-on implementation and comparison of **Logistic Regression** and **Multi-Layer Perceptron (MLP)** built *entirely from scratch* using NumPy — demonstrating when simple models outperform deep learning on tabular data.

---

## 📌 Overview

This project explores a fundamental machine learning question:

> **Do we really need deep learning for tabular data?**

To answer this, we:
- Implement **Logistic Regression** (baseline linear model)
- Implement a **Multi-Layer Perceptron (MLP)** (neural network)
- Train both using **gradient descent from scratch**
- Compare performance on a real-world dataset

---

## 🧠 Key Highlights

- ✅ No use of sklearn models (pure NumPy implementation)
- ✅ End-to-end ML pipeline (preprocessing → training → evaluation)
- ✅ Custom implementation of:
  - Forward propagation
  - Backward propagation (backpropagation)
  - Loss functions
  - Gradient descent
- ✅ Real-world dataset (Loan Approval Prediction)
- ✅ Insightful comparison of model performance

---

## 📊 Problem Statement

Predict whether a loan application will be **approved or rejected** based on applicant features such as income, credit score, and assets.

- **Type**: Binary Classification  
- **Dataset Source**: Kaggle  
- **Samples**: 4269  
- **Features**: 11  

---

## ⚙️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn *(only for preprocessing)*

---

## 🔄 Workflow

1. Data Loading  
2. Data Cleaning & Preprocessing  
3. Train-Test Split  
4. Model Training  
5. Evaluation  
6. Visualization  

---

## 🏗️ Model Implementations

### 🔹 Logistic Regression
- Sigmoid activation  
- Binary Cross-Entropy Loss  
- Gradient Descent  

### 🔹 Multi-Layer Perceptron (MLP)
- ReLU (hidden layers)  
- Sigmoid (output layer)  
- Backpropagation  

---

## 📈 Results

| Metric      | Logistic Regression | MLP        |
|------------|--------------------|------------|
| Accuracy   | **0.9379**         | 0.8817     |
| Precision  | **0.9193**         | 0.8535     |
| Recall     | **0.9164**         | 0.8297     |
| F1 Score   | **0.9178**         | 0.8414     |

---

## 🔍 Key Insights

- Logistic Regression outperformed MLP  
- Simpler models can work better for structured data  
- Neural networks require tuning and more data  

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/linear-vs-mlp-from-scratch.git
cd linear-vs-mlp-from-scratch
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

```
.
├── notebook.ipynb
├── data/
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Add regularization  
- Try tree-based models  

---

## ⭐ If You Found This Useful

Give this repo a ⭐

---

## 👨‍💻 Author

**Saurabh Ambar**
Data | Engineer | AIML Enthusiast
