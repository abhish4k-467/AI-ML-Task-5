# AI-ML-Task-5

## By Abhishek Mitra

# Decision Tree vs Random Forest Classifier

This project demonstrates how to train and evaluate a Decision Tree and a Random Forest classifier using a supervised learning dataset. The goal is to compare the models, visualize the decision tree, analyze overfitting, interpret feature importances, and validate results using cross-validation.

---

## 📌 Objectives

1. **Train a Decision Tree Classifier and visualize the tree**
2. **Analyze overfitting and control tree depth**
3. **Train a Random Forest and compare accuracy**
4. **Interpret feature importances**
5. **Evaluate using cross-validation**

---

## ✅ Results Summary

### 🔍 Decision Tree Classifier (`dt_model`)

| Metric                    | Value        |
|---------------------------|--------------|
| Training Accuracy         | **100.00%**  |
| Testing Accuracy          | **98.54%**   |
| Cross-Validation Accuracy | **1.000**    |

### 🌲 Random Forest Classifier (`rf_model`)

| Metric                    | Value        |
|---------------------------|--------------|
| Training Accuracy         | **100.00%**  |
| Testing Accuracy          | **98.54%**   |
| Cross-Validation Accuracy | **0.994**    |

---

## 📊 Model Interpretations

### Decision Tree Visualization

- The tree was visualized using `plot_tree` from `sklearn.tree`, showing how the model makes decisions at each split.
- Depth control was applied to reduce overfitting without sacrificing accuracy.

### Overfitting Analysis

- Both models achieved 100% training accuracy, but generalization was confirmed with high test accuracy.
- Overfitting was mitigated using tree depth tuning and ensemble methods like Random Forest.

### Feature Importances

- Feature importance scores from the Random Forest model were analyzed to understand which features contributed most to the predictions.

  ![image](https://github.com/user-attachments/assets/6db90e6d-2a1f-42f2-a75c-1a5a067e79cd)
  

  ![image](https://github.com/user-attachments/assets/bc799c42-dffa-49de-a85c-740f97381d3c)



---

## 🧪 Cross-Validation

- **Decision Tree**: Achieved a perfect cross-validation mean score of **1.000**, indicating excellent generalization.
- **Random Forest**: Achieved a strong cross-validation mean score of **0.994**, showing consistent performance.
