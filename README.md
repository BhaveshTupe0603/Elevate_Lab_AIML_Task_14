# 🏆 Task 14: Model Comparison

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange?logo=scikit-learn)

## 📖 Overview
**Task 14** is about decision making. We moved beyond training a single model to **benchmarking** multiple algorithms against each other. Using the Breast Cancer dataset, we evaluated 5 different models to find the optimal solution.

## ⚙️ Workflow
1.  **Preprocessing:** Standardized features (`StandardScaler`) and split data 80/20.
2.  **Benchmarking:** Trained Logistic Regression, Decision Tree, Random Forest, SVM, and KNN.
3.  **Evaluation:** Compared models using a pandas DataFrame of metrics (Accuracy, Precision, Recall, F1).
4.  **Selection:** Identified the top performer based on F1-Score.

## 📊 Comparison Results

| Model | Accuracy | F1 Score |
| :--- | :--- | :--- |
| **SVM** | **98.2%** | **0.986** |
| **Logistic Regression** | 97.4% | 0.979 |
| **Random Forest** | 96.5% | 0.972 |
| **Decision Tree** | 94.7% | 0.958 |
| **KNN** | 94.7% | 0.958 |

*Note: SVM achieved the highest performance with perfect Recall (1.0), meaning it identified all malignant cases correctly.*

## 🖼️ Deliverables
<img width="1010" height="547" alt="image" src="https://github.com/user-attachments/assets/afa2503e-8ab1-44e2-adaf-36965b805031" />

*(Note: Save the bar chart from the notebook and link it here)*

## 📂 Files
* [📓 Jupyter Notebook](./Task 14.ipynb)
* [💾 Best Model (.pkl)](./best_model.pkl)
